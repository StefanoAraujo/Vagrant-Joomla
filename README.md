<b>Programs required:</b>

- <a href="http://cygwin.com/install.html">Cygwin</a> (dont forget to install git and ssh packages)<br />
- <a href="http://www.vagrantup.com/downloads.html">Vagrant</a><br />
- <a href="https://www.virtualbox.org/wiki/Downloads">Virtual box</a><br />
- <a href="http://git-scm.com/downloads">Git bash</a>


<b>Instructions:</b>

- git clone https://github.com/guidsen/Vagrant-Joomla.git
- ssh into your vagrant box (cmd: vagrant ssh)
- sudo apt-get install phpmyadmin
- echo -e "Include /etc/phpmyadmin/apache.conf" | sudo tee -a /etc/apache2/apache2.conf
- sudo service apache2 restart
