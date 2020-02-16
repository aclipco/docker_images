FROM centos:latest
RUN yum install wget unzip -y
RUN wget https://releases.hashicorp.com/terraform/0.12.19/terraform_0.12.19_linux_amd64.zip
RUN unzip terraform_0.12.19_linux_amd64.zip
RUN mv terraform /bin