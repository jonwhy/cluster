FROM registry.cn-shenzhen.aliyuncs.com/huanggenghuai/my_first:v1
MAINTAINER huanggenghuai
#启动服务
CMD /etc/init.d/php-fpm start \
   && nginx -c /etc/nginx/nginx.conf \
&& tail -f /var/log/nginx/error.log
EXPOSE 80
######结束#########
