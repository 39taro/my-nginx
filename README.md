# dev enviroments
```bash
$ cat /etc/debian_version
9.8
$ php -v
PHP 7.3.2
$ mysql --version
mysql  Ver 15.1 Distrib 10.1.37-MariaDB
$ nginx -v
nginx version: nginx/1.10.3
```

# nginx
```bash
$ sudo su -
$ mv /etc/nginx /etc/nginx
$ git clone https://github.com/39taro/my-nginx.git nginx
$ vim /etc/nginx/nginx.conf
# include /home/39taro/app/my-nginx/conf.d/*.conf;
$ exit
$ mkdir ~/app
$ cd app
$ git clone https://github.com/39taro/my-nginx.git
```
# php-fpm
```bash
$ sudo cp ~/app/my-nginx/php-fpm/pool.d/www.conf /etc/php/7.3/fpm/pool.d/www.conf
$ /etc/init.d/php7.3-fpm restart
```