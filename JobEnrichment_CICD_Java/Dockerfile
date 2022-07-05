FROM jenkinsci/blueocean



ENV JENKINS_USER admin
ENV JENKINS_PASS admin


# Skip initial setup
ENV JAVA_OPTS -Djenkins.install.runSetupWizard=false
ENV JENKINS_OPTS -httpPort=8099
USER root

RUN apk add maven
EXPOSE 8099:8099
