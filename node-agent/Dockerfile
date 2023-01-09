FROM jenkins/agent:alpine-jdk11
USER root
RUN apk add nodejs npm
#smoke test
RUN node --version
USER jenkins
CMD ["bash"]