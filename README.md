OpenAI-dev_ops

开发环境配置

1.配置git仓库

2.阿里云服务器

3.docker配置-使用vm进行远程链接

4.portainer使用

5.nginx配置

linux命令

docker run \
--name Nginx \
-p 80:80 \
-v /data/nginx/logs:/var/log/nginx \
-v /data/nginx/html:/usr/share/nginx/html \
-v /data/nginx/conf/nginx.conf:/etc/nginx/nginx.conf \
-v /data/nginx/conf.d:/etc/nginx/conf.d \
-v /data/nginx/ssl:/etc/nginx/ssl/ \
--privileged=true -d --restart=always nginx

