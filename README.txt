
skynet天网主要是用于简单的网络协议应用层过滤，配合Haproxy以及监控接口实现流量监控、ip黑白名单过滤、流量预警。


使用说明：
centos：
    yum install libffi
    yum install libffi-devel
ubuntu：
    apt-get install libffi-dev
    
执行setup.sh时，需要先把setup.sh转换成unix文件，且chmod +x setup.sh
    
根据私有生成证书
openssl req -new -key privkey.pem -out cert.csr
