FROM rhel7.7:latest

RUN yum upgrade -y && yum install -y git curl ca-certificates && yum groupinstall -y "Development Tools" && yum clean all -y

RUN yum install -y postgres-client

CMD ["/bin/bash"]
FROM rhel7.7:latest

RUN yum upgrade -y && yum install -y git curl ca-certificates && yum groupinstall -y "Development Tools" && yum clean all -y

RUN yum install -y postgres-client

CMD ["/bin/bash"]
