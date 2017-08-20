
# Docker这个dockerfile是基于nimmis/alpine-apache-php5：latest 安装了一些需要的php扩展，xdebug和伪静态没有启动

sed -i 's/#LoadModule rewrite_module modules/mod_rewrite.so/LoadModule rewrite_module modules/mod_rewrite.so'/web/config/conf.
d/httpd.conf

/etc/apache2/httpd.conf
sed -i 's/\#LoadModule rewrite_module modules/mod_rewrite.so/LoadModule rewrite_module modules/mod_rewrite.so'/etc/apache2/httpd.conf
sed  's/#LoadModule rewrite_module modules/mod_rewrite.so/LoadModule rewrite_module modules/mod_rewrite.so' /etc/apache2/httpd.conf
mysql: docker pull wangxian/alpine-mysql:latest  

