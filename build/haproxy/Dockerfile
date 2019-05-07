# sd-swoole
#FROM  registry.cn-hangzhou.aliyuncs.com/carfield-centos/centos7:7
FROM registry.cn-beijing.aliyuncs.com/flyhope/centos

MAINTAINER huanggenghuai
#RUN wget -O /etc/yum.repos.d/CentOS-Base.repo http://mirrors.aliyun.com/repo/Centos-7.repo
#安装haproxy
#RUN yum  update
RUN yum  install haproxy -y
#CMD ["haproxy","-D","-f","/etc/haproxy/haproxy.cfg"]
#RUN haproxy -d -f  /etc/haproxy/haproxy.cfg
#启动服务
#CMD haproxy -f /etc/haproxy/haproxy.cfg
#CMD haproxy /etc/haproxy/haproxy.cfg
#CMD ["echo","i am haunggenghuai"]
#ENTRYPOINT ["haproxy"]
CMD ["haproxy","-f","/etc/haproxy/haproxy.cfg","-d"]
#ENTRYPOINT ["haproxy", "-f"]
