# The deployment of a web server

## XAMPP (for rookies)

If you are extremely new to web development, and you are not interested in how a server works,
[XAMPP](https://www.apachefriends.org/index.html) can help you to setup a PHP + MySQL + Apache server in half an hour.

XAMPP runs on Windows, Linux and Mac OS.

It is not recommended, but I have to put it here because it's really the esiest way.
You can find more information about it on the official website above.

## Try to install the softwares on your own

If you didn't open the XAMPP website, or you are not deploying your first web server, the following will hrlp you.

### Windows

First, suppose you have chocolatey installed, it's not difficult at all.
```
choco install -y php mysql apache-httpd
```
Make sure you have a stable Internet connection and the packages will be installed after several minutes.

### Linux

Most of Linux distributions have these packages in package manager. For example, in Ubuntu > 16.04
```
sudo apt-get install -y apache2 php
sudo apt-get install -y php7.0-fpm php7.0-mysql php7.0-common php7.0-mbstring php7.0-gd php7.0-json php7.0-cli php7.0-curl libapache2-mod-php7.0
sudo apt-get install -y mysql-server-5.7
```

### Mac OS

Similar to Linux, will be completed later.


## Try to edit config files on your own



