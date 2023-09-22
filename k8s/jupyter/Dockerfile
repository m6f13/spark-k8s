FROM jupyter/base-notebook:latest

USER root

# Install Java
RUN apt-get update -y && \
    apt-get install -y openjdk-11-jdk && \
    apt-get clean

USER $NB_UID
