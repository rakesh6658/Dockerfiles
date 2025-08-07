FROM almalinux
RUN yum install -y iputils && yum clean all

CMD ["ping", "-c", "5", "google.com"]