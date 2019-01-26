# linux
Some linux stuff to speed up production

#Nginx, MariaDB, PHP7.2, PHPMyAdmin:

sudo apt install nginx

sudo systemctl enable nginx

sudo systemctl start nginx

sudo chown www-data:www-data /usr/share/nginx/html -R

sudo apt install mariadb-server mariadb-client

sudo systemctl start mariadb

sudo systemctl enable mariadb

sudo mysql_secure_installation

sudo apt install php7.2 php7.2-fpm php7.2-mysql php-common php7.2-cli php7.2-common php7.2-json php7.2-opcache php7.2-readline 
php7.2-mbstring php7.2-xml php7.2-gd php7.2-curl

sudo systemctl start php7.2-fpm

sudo systemctl enable php7.2-fpm

sudo apt-get install phpmyadmin php-mbstring php-gettext

sudo phpenmod mcrypt

sudo phpenmod mbstring

#Visual Studio Code

sudo apt-get install snapd snapd-xdg-open

sudo snap install --classic vscode

sudo snap refresh vscode


#Sublime Text

#Filezilla
sudo apt-get install filezilla

#Google Chrome
sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'

wget -q -O - https://dl.google.com/linux/linux_signing_key.pub | sudo apt-key add -

sudo apt-get update

sudo apt-get install google-chrome-stable

#MySQL Workbench
sudo apt install mysql-workbench

