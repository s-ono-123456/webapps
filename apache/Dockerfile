FROM centos:7
RUN yum -y update && yum clean all
RUN yum -y install httpd httpd-devel gcc* make && yum clean all
COPY httpd.conf /etc/httpd/conf/
COPY run-httpd.sh /run-httpd.sh
RUN chmod -v +x /run-httpd.sh
CMD ["/run-httpd.sh"]