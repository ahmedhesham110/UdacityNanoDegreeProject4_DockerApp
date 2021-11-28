# UdacityNanoDegreeProject4_DockerApp
[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://circleci.com/gh/circleci/circleci-docs)

## Project Overview

The project goal is to test docker knowledge through simple app

### Project Tasks

* Testing the project code using linting
* Completing a Dockerfile to containerize this application
* Deploying your containerized application using Docker and make a prediction
* Improving the log statements in the source code for this application
* Configuing Kubernetes and create a Kubernetes cluster
* Deploying a container using Kubernetes and make a prediction
* Uploading a complete Github repo with CircleCI to indicate that your code has been tested

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
