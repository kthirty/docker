# 说明

这是一个Nginx的Docker-Compose 文件

# 注意

nginx 内部已经自己存在nginx.conf文件，且已自动引入 `/etc/nginx/conf.d/*.conf` 文件夹下的文件

- `/var/www` 用来存放静态资源
- 证书文件存放在`/etc/letsencrypt` ， **注意！这里是绝对路径**

 
