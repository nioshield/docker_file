# docker_file
# nginx
* NGINX_DEVEL_KIT=0.3.0
* LUA_NGINX_MODULE=0.10.8
* NGINX=1.7.10
* LUAJIT=2.0.4

# php7.0
新增扩展
* redis
* amp

# golang 
* version 1.8


# 安装

* cd ./docker_file/ngx-lua && docker build -t="nginx_lua" .
* docker run -idt --name="nginx" nginx_lua

# 使用
* docker exec -it nginx /bin/bash
  
  
