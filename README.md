# aws
Ec2 instance with Apache2 and PHP &amp; MySQL
# Change Repository for old php version

sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt-get install php8.1

sudo apt-get install curl git

curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

sudo apt-get update

sudo apt-get install apache2

sudo systemctl status apache2

sudo systemctl enable apache2

try ec2 url without https:// 

sudo systemctl restart apache2

sudo apt-get update
sudo apt-get install -y \
    php8.1-bcmath \
    php8.1-ctype \
    php8.1-curl \
    php8.1-dom \
    php8.1-fileinfo \
    php8.1-ftp \
    php8.1-gd \
    php8.1-hash \
    php8.1-iconv \
    php8.1-json \
    php8.1-mbstring \
    php8.1-openssl \
    php8.1-pdo \
    php8.1-tokenizer \
    php8.1-xml \
    php8.1-zip


sudo apt-get install -y php8.1-xml
sudo apt-get install -y php8.1-zip


sudo systemctl restart apache2

scp -i "file.pem" file.zip ubuntu@ec2-13-234-59-9.ap-south-1.compute.amazonaws.com:/var/www/html





