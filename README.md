# INATE

Inate landing page template

* [Getting started](#getting-started)

## Getting started
* Jenkins container monitors this git and on changes causes a pull 
* Jenkins pipeline then builds the docker image from the .Dockerfile in this repo
* Docker file copies all contents to a nginx base image and ngingx webserver is started
