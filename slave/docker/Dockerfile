FROM eeacms/jenkins:ubuntu-slave

USER root
RUN groupadd -g 999 docker
RUN usermod -aG docker jenkins

USER jenkins
