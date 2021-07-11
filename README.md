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
<p>Download</p>
<pre>sudo apt install git</pre>
<p>Check version</p>
<pre>git --version</pre>


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


    
