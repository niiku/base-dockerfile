FROM quay.io/openshift/origin-cli:v3.11.0
USER root
RUN yum install -y bc gettext git java-1.8.0-openjdk-headless lsof rsync tar unzip which zip bzip2 && yum clean all
USER 1001