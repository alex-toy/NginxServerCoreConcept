# Nginx Server Core Concept

- How Nginx works with core concept
- How to install Nginx- compile based and yum base both
- Nginx core Architecture
- Hosting Static and Dynamic websites
- Hosting video streaming by using Nginx as a reverse proxy server
- Log analysis to identify issue and fixing
- Securing Nginx by fine tuning configuration and adding security add ons.
- Load balancing of Dynamic Application using Nginx

## Installation

https://www.phusionpassenger.com/library/install/nginx/install/oss/tarball/

sudo mkdir /opt/installs
cd /opt/installs
sudo mkdir /APPS
wget http://ftp.pcre.org/pub/pcre/pcre-8.00.tar.gz

sudo apt-get update
sudo apt-get install -y ruby rake

PATH=/opt/installs/passenger-6.0.23/bin:$PATH
export PATH

passenger-install-nginx-module

https://nginx.org/en/linux_packages.html#Ubuntu

sudo systemctl start nginx

curl localhost

sudo systemctl stop nginx

<img src="/pictures/install.png" title="installation"  width="900">

## 