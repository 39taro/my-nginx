# 設定
```bash
$ sudo su -
$ mv /etc/nginx /etc/nginx
$ git clone https://github.com/39taro/my-nginx.git nginx
# include /home/39taro/app/my-nginx/conf.d/*.conf;の
# 39taroを自分のusernameに変える
$ vim /etc/nginx/nginx.conf
$ exit
$ mkdir ~/app
$ cd app
$ git clone https://github.com/39taro/my-nginx.git
```