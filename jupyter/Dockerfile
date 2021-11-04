## Basic container image to jupyter notebooks
FROM jupyter/base-notebook:latest
## Install package dependencies
WORKDIR /home/docker_worker/jupyter/
COPY ./requirements.pip ./requirements.pip
RUN pip install -r requirements.pip
