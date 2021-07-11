# Ubuntu_Basic_Software

<h3>Fix: "Error Unable Update Ubuntu 19.04"</h3>
<a href="https://www.digitalocean.com/community/questions/unable-to-apt-update-my-ubuntu-19-04">Link Reference</a> 
<pre>sudo sed -i -re 's/([a-z]{2}\.)?archive.ubuntu.com|security.ubuntu.com/old-releases.ubuntu.com/g' /etc/apt/sources.list
sudo apt-get update && sudo apt-get dist-upgrade
</pre>

<h3>Install Google Chrome</h3>
<a href="https://linuxize.com/post/how-to-install-google-chrome-web-browser-on-ubuntu-18-04/">Link Reference</a>
<pre>wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
</pre>

<h3>Install Git</h3>
<pre>sudo apt install git</pre>

<h3>Install Unikey</h3> 
<a href="https://github.com/teni-ime/ibus-teni">Link Reference</a>
<pre>sudo add-apt-repository ppa:teni-ime/ibus-teni
sudo apt-get update
sudo apt-get install ibus-teni
ibus restart
</pre>                                                                                                                               
While installing, if there is error message:
<span><i>E: Could not get lock /var/lib/dpkg/lock-frontend - open (11: Resource temporarily unavailable)  
E: Unable to acquire the dpkg frontend lock (/var/lib/dpkg/lock-frontend),   
 is another process using it?</i></span>
 
<p>Then write command: </p>
<pre>sudo killall apt apt-get</pre>   

<readme-toc data-catalyst="">

    <div id="readme" class="Box md js-code-block-container Box--responsive">

      <div class="d-flex js-sticky js-position-sticky top-0 border-top-0 border-bottom p-2 flex-items-center flex-justify-between color-bg-primary rounded-top-2" style="position: sticky; z-index: 90; top: 0px !important;" data-original-top="0px">
        <div class="d-flex flex-items-center">
            <details data-target="readme-toc.trigger" data-menu-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;trigger&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-menu-hydro-click-hmac="20c15f0885e41cb842a7cca3e330406bc0d3567a5aa54ea149319d58d9e58818" class="dropdown details-reset details-overlay">
  <summary class="btn btn-octicon m-0 mr-2 p-2" aria-haspopup="menu" aria-label="Table of Contents" role="button">
    <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-list-unordered">
    <path fill-rule="evenodd" d="M2 4a1 1 0 100-2 1 1 0 000 2zm3.75-1.5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"></path>
</svg>
  </summary>

  <details-menu class="SelectMenu" role="menu">
    <div class="SelectMenu-modal rounded-3 mt-1" style="max-height:340px;">
      <div class="SelectMenu-list SelectMenu-list--borderless p-2" style="overscroll-behavior: contain;">

          <a role="menuitem" class="filter-item py-1 text-emphasized" style="padding-left: 12px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#ibus-teni---a-vietnamese-input-method-editor-for-ibus" aria-current="page">IBus Teni - a Vietnamese Input Method Editor for IBus</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#teni-là-gì-">Teni là gì ?</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#sơ-lược-tính-năng">Sơ lược tính năng</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#cài-đặt-và-cấu-hình">Cài đặt và cấu hình</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#cài-đặt-ubuntu">Cài đặt (Ubuntu)</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#cấu-hình">Cấu hình</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 36px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#gỡ-bỏ">Gỡ bỏ</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#sử-dụng">Sử dụng</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#các-phiên-bản">Các phiên bản</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#góp-ý-và-báo-lỗi">Góp ý và báo lỗi</a>
          <a role="menuitem" class="filter-item py-1 " style="padding-left: 24px;" data-action="click:readme-toc#blur" data-targets="readme-toc.entries" data-hydro-click="{&quot;event_type&quot;:&quot;repository_toc_menu.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;entry&quot;,&quot;repository_id&quot;:138488959,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="5cb40f1b22ccef88f2796c0bfb3518b5acce9693065419727c5409573bf9cace" href="#giấy-phép">Giấy phép</a>
      </div>
    </div>
  </details-menu>
</details>

          <h2 class="Box-title">
            <a href="#readme" data-view-component="true" class="Link--primary">README.md</a>
          </h2>
        </div>
      </div>

          <div class="Popover anim-scale-in js-tagsearch-popover" hidden="" data-tagsearch-url="/teni-ime/ibus-teni/find-definition" data-tagsearch-ref="master" data-tagsearch-path="README.md" data-tagsearch-lang="Markdown" data-hydro-click="{&quot;event_type&quot;:&quot;code_navigation.click_on_symbol&quot;,&quot;payload&quot;:{&quot;action&quot;:&quot;click_on_symbol&quot;,&quot;repository_id&quot;:138488959,&quot;ref&quot;:&quot;master&quot;,&quot;language&quot;:&quot;Markdown&quot;,&quot;originating_url&quot;:&quot;https://github.com/teni-ime/ibus-teni&quot;,&quot;user_id&quot;:85974492}}" data-hydro-click-hmac="00d346daf4fde5f939bbfc56eae7ffa5c39e8c80f3054810dd60599ebe27c9a2">
  <div class="Popover-message Popover-message--large Popover-message--top-left TagsearchPopover mt-1 mb-4 mx-auto Box color-shadow-large">
    <div class="TagsearchPopover-content js-tagsearch-popover-content overflow-auto" style="will-change:transform;">
    </div>
  </div>
</div>

        <div data-target="readme-toc.content" class="Box-body px-5 pb-5">
          <article class="markdown-body entry-content container-lg" itemprop="text"><h1><a id="user-content-ibus-teni---a-vietnamese-input-method-editor-for-ibus" class="anchor" aria-hidden="true" href="#ibus-teni---a-vietnamese-input-method-editor-for-ibus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><a href="https://github.com/teni-ime/ibus-teni">IBus Teni - a Vietnamese Input Method Editor for IBus</a></h1>
<p><a href="https://travis-ci.org/teni-ime/ibus-teni" rel="nofollow"><img src="https://camo.githubusercontent.com/8839c3a20eab68a79e0633abc906349fe433f0342eddd4eaf977dff8f44096b3/68747470733a2f2f7472617669732d63692e6f72672f74656e692d696d652f696275732d74656e692e7376673f6272616e63683d6d6173746572" alt="Build Status" data-canonical-src="https://travis-ci.org/teni-ime/ibus-teni.svg?branch=master" style="max-width:100%;"></a>
<a href="https://github.com/teni-ime/ibus-teni/releases/latest"><img src="https://camo.githubusercontent.com/69967457320975c03eaf2acd575a3fadd949605c60f71135509f5e9e48915b86/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f74656e692d696d652f696275732d74656e692e737667" alt="GitHub release" data-canonical-src="https://img.shields.io/github/release/teni-ime/ibus-teni.svg" style="max-width:100%;"></a>
<a href="https://opensource.org/licenses/GPL-3.0" rel="nofollow"><img src="https://camo.githubusercontent.com/9e54064fb698af20a2b6089b4f16ec3e31f31f72b47f15a5bb215bfd2e41d1b2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d47504c25323076332d626c75652e737667" alt="License: GPL v3" data-canonical-src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" style="max-width:100%;"></a>
<a href="https://github.com/teni-ime/ibus-teni/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-g%C3%B3p-%C3%BD%2C-b%C3%A1o-l%E1%BB%97i"><img src="https://camo.githubusercontent.com/f5054ffcd4245c10d3ec85ef059e07aacf787b560f83ad4aec2236364437d097/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f6e747269627574696f6e732d77656c636f6d652d627269676874677265656e2e7376673f7374796c653d666c6174" alt="contributions welcome" data-canonical-src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat" style="max-width:100%;"></a></p>
<p>Copyright 2018, Nguyen Cong Hoang &lt;<a href="mailto:hoangnc.jp@gmail.com">hoangnc.jp@gmail.com</a>&gt;.</p>
<p>IBus Teni is a Vietnamese Input Method Editor (IME) for IBus.</p>
<p>IBus Teni là một bộ gõ tiếng Việt cho IBus.</p>
<h2><a id="user-content-teni-là-gì-" class="anchor" aria-hidden="true" href="#teni-là-gì-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Teni là gì ?</h2>
<ul>
<li>Teni là kết hợp <strong>Te</strong>lex và V<strong>ni</strong> - 2 kiểu gõ tiếng Việt phổ biến nhất.</li>
<li>Teni cũng là kiểu gõ mặc định của bộ gõ này, vừa gõ được Telex, vừa gõ được Vni.</li>
</ul>
<h3><a id="user-content-sơ-lược-tính-năng" class="anchor" aria-hidden="true" href="#sơ-lược-tính-năng"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Sơ lược tính năng</h3>
<ul>
<li>Chỉ bảng mã Unicode</li>
<li>3 kiểu gõ:
<ul>
<li><strong>Kiểu gõ Teni</strong> (Telex + Vni, không cho phép gõ nhanh ư, ơ bằng w, [, ])</li>
<li><strong>Kiểu gõ Vni</strong></li>
<li><strong>Kiểu gõ Telex</strong> (cho phép gõ nhanh ư, ơ bằng w, [, ])</li>
</ul>
</li>
<li>2 kiểu đánh dấu thanh:
<ul>
<li><strong>Dấu thanh chuẩn</strong></li>
<li><strong>Dấu thanh kiểu mới</strong></li>
</ul>
</li>
<li>Gõ dấu tự do, đánh dấu thanh bằng từ điển</li>
<li>Có danh sách loại trừ ứng dụng không dùng bộ gõ</li>
</ul>
<h2><a id="user-content-cài-đặt-và-cấu-hình" class="anchor" aria-hidden="true" href="#cài-đặt-và-cấu-hình"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Cài đặt và cấu hình</h2>
<h3><a id="user-content-cài-đặt-ubuntu" class="anchor" aria-hidden="true" href="#cài-đặt-ubuntu"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Cài đặt (Ubuntu)</h3>
<div class="highlight highlight-source-shell position-relative"><pre>sudo add-apt-repository ppa:teni-ime/ibus-teni
sudo apt-get update
sudo apt-get install ibus-teni
ibus restart</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo add-apt-repository ppa:teni-ime/ibus-teni
sudo apt-get update
sudo apt-get install ibus-teni
ibus restart
" tabindex="0" role="button">
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-clippy js-clipboard-clippy-icon m-2">
    <path fill-rule="evenodd" d="M5.75 1a.75.75 0 00-.75.75v3c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-3a.75.75 0 00-.75-.75h-4.5zm.75 3V2.5h3V4h-3zm-2.874-.467a.75.75 0 00-.752-1.298A1.75 1.75 0 002 3.75v9.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-9.5a1.75 1.75 0 00-.874-1.515.75.75 0 10-.752 1.298.25.25 0 01.126.217v9.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-9.5a.25.25 0 01.126-.217z"></path>
</svg>
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-check js-clipboard-check-icon color-text-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p><strong>Lệnh bên dưới cho phép đọc event chuột, không bắt buộc nhưng cần để ibus-teni hoạt động tốt</strong></p>
<div class="highlight highlight-source-shell position-relative"><pre>sudo usermod -a -G input <span class="pl-smi">$USER</span></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo usermod -a -G input $USER
" tabindex="0" role="button">
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-clippy js-clipboard-clippy-icon m-2">
    <path fill-rule="evenodd" d="M5.75 1a.75.75 0 00-.75.75v3c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-3a.75.75 0 00-.75-.75h-4.5zm.75 3V2.5h3V4h-3zm-2.874-.467a.75.75 0 00-.752-1.298A1.75 1.75 0 002 3.75v9.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-9.5a1.75 1.75 0 00-.874-1.515.75.75 0 10-.752 1.298.25.25 0 01.126.217v9.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-9.5a.25.25 0 01.126-.217z"></path>
</svg>
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-check js-clipboard-check-icon color-text-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p><em>Cài đặt cho các bản Linux khác và hướng dẫn cài đặt từ mã nguồn: <a href="https://github.com/teni-ime/ibus-teni/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-c%C3%A0i-%C4%91%E1%BA%B7t">wiki</a></em></p>
<h3><a id="user-content-cấu-hình" class="anchor" aria-hidden="true" href="#cấu-hình"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Cấu hình</h3>
<ol>
<li><a href="https://github.com/teni-ime/ibus-teni/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-c%E1%BA%A5u-h%C3%ACnh#1-keyboard-input-method-system-ibus">Keyboard input method system: IBus</a></li>
<li><a href="https://github.com/teni-ime/ibus-teni/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-c%E1%BA%A5u-h%C3%ACnh#2-add-an-input-source-vietnameseteni">Add an input source: Vietnamese(Teni)</a></li>
</ol>
<h3><a id="user-content-gỡ-bỏ" class="anchor" aria-hidden="true" href="#gỡ-bỏ"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Gỡ bỏ</h3>
<div class="snippet-clipboard-content position-relative"><pre><code>sudo apt remove ibus-teni
ibus restart
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt remove ibus-teni
ibus restart
" tabindex="0" role="button">
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-clippy js-clipboard-clippy-icon m-2">
    <path fill-rule="evenodd" d="M5.75 1a.75.75 0 00-.75.75v3c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-3a.75.75 0 00-.75-.75h-4.5zm.75 3V2.5h3V4h-3zm-2.874-.467a.75.75 0 00-.752-1.298A1.75 1.75 0 002 3.75v9.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 13.25v-9.5a1.75 1.75 0 00-.874-1.515.75.75 0 10-.752 1.298.25.25 0 01.126.217v9.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-9.5a.25.25 0 01.126-.217z"></path>
</svg>
      <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-check js-clipboard-check-icon color-text-success d-none m-2">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2><a id="user-content-sử-dụng" class="anchor" aria-hidden="true" href="#sử-dụng"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Sử dụng</h2>
<ul>
<li>Dùng phím tắt mặc định của IBus (thường là ⊞Win+Space) để chuyển đổi giữa các bộ gõ</li>
<li>IBus-Teni dùng pre-edit để xử lý phím gõ, mặc định sẽ có gạch chân chữ khi đang gõ</li>
<li><strong>Khi pre-edit chưa kết thúc mà nhấn chuột vào chỗ khác thì có 3 khả năng xảy ra tùy chương trình</strong>
<ul>
<li><strong>Chữ đang gõ bị mất</strong></li>
<li><strong>Chữ đang gõ được commit vào vị trí mới con trỏ</strong></li>
<li><strong>Chữ đang gõ được commit vào vị trí cũ</strong></li>
</ul>
</li>
<li><strong>Vì vậy đừng quên commit: khi gõ chỉ một chữ, hoặc chữ cuối câu, hoặc sửa chữ giữa câu: nhấn phím <em>Ctrl</em> để commit.</strong></li>
</ul>
<h2><a id="user-content-các-phiên-bản" class="anchor" aria-hidden="true" href="#các-phiên-bản"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Các phiên bản</h2>
<ul>
<li>Phiên bản thử nghiệm không công khai hoàn thành vào cuối tháng 5/2018</li>
<li>Phiên bản thử nghiệm công khai phát hành vào đầu tháng 7/2018</li>
<li>Phiên bản chính thức phát hành vào ngày 29/7/2018</li>
</ul>
<p>Xem trang <a href="https://github.com/teni-ime/ibus-teni/releases">release</a> để biết chi tiết các phiên bản đã phát hành.</p>
<h2><a id="user-content-góp-ý-và-báo-lỗi" class="anchor" aria-hidden="true" href="#góp-ý-và-báo-lỗi"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Góp ý và báo lỗi</h2>
<p>Xem <a href="https://github.com/teni-ime/ibus-teni/wiki/H%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-g%C3%B3p-%C3%BD%2C-b%C3%A1o-l%E1%BB%97i">hướng dẫn</a></p>
<h2><a id="user-content-giấy-phép" class="anchor" aria-hidden="true" href="#giấy-phép"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Giấy phép</h2>
<p>Toàn bộ code IBus Teni được viết bởi Nguyen Cong Hoang và những người đóng góp được phát hành dưới giấy phép
<a href="https://opensource.org/licenses/GPL-3.0" rel="nofollow">GNU General Public License version 3</a>.</p>
<p>Code trong thư mục <a href="/teni-ime/ibus-teni/blob/master/src/ibus-teni/vendor">src/ibus-teni/vendor</a> là của các bên thứ 3,
xem các thông báo bản quyền trong từng thư mục con.</p>
<ul>
<li>godbus: xem <a href="/teni-ime/ibus-teni/blob/master/src/ibus-teni/vendor/github.com/godbus/dbus/README.markdown">src/ibus-teni/vendor/github.com/godbus/dbus/README.markdown</a></li>
<li>goibus: xem <a href="/teni-ime/ibus-teni/blob/master/src/ibus-teni/vendor/github.com/sarim/goibus/README.md">src/ibus-teni/vendor/github.com/sarim/goibus/README.md</a></li>
</ul>
<p>Dữ liệu từ điển trong thư mục <a href="/teni-ime/ibus-teni/blob/master/dict">dict</a>: xem <a href="/teni-ime/ibus-teni/blob/master/dict/LICENSE">dict/LICENSE</a></p>
<ul>
<li><a href="http://www.informatik.uni-leipzig.de/~duc/Dict/" rel="nofollow">Dữ liệu từ điển tiếng Việt của Ho Ngoc Duc</a></li>
<li><a href="https://vi.wiktionary.org/wiki/Trang_Ch%C3%ADnh" rel="nofollow">Wiktionary tiếng Việt</a></li>
<li><a href="https://sites.google.com/site/ngo2uochung/research/dsviettat-tieng-viet" rel="nofollow">Danh sách viết tắt trong tiếng Việt của QUOC-HUNG NGO</a></li>
</ul>
</article>
        </div>
    </div>

  </readme-toc>
    
    
    
    
    
    
    
