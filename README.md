[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://circleci.com/gh/circleci/circleci-docs)

### This is a Udacity DevOps Project

In this project, I will operationalize a Machine Learning Microservice API.
This project goal is to operationalize this working, machine learning microservice using kubernetes, which is an open-source system for automating the management of containerized applications. In this project I will:

Test the project code using linting
Complete a Dockerfile to containerize this application
Deploy a containerized application using Docker and make a prediction
Improve the log statements in the source code for this application
Configure Kubernetes and create a Kubernetes cluster
Deploy a container using Kubernetes and make a prediction
Upload a complete Github repo with CircleCI to indicate that the code has been tested

### Instructions
First Setup a python virtual environment and activate it
python3 -m venv ~/.devops
source ~/.devops/bin/activate

#Install the necessary dependencies
make install

#Run the Main app
1. Run in Docker:  `./run_docker.sh`
2. Run in Kubernetes:  `./run_kubernetes.sh`
3. Run the make_prediction.sh script

### Files

1. Makefile: Makefile for setup and install
2. requirements.txt: Libs for Python
3. Dockerfile: Dockerfile
4. app.py: Application for Performing a sklearn prediction
5. model_data/boston_housing_prediction.joblib: Pretrained sklearn model for the API
6. run_docker.sh: script for easy docker run
7. run_kubernetes.sh: runs a kubernetes cluster
8. make_prediction.sh: script that parse the payload for sklearn
9. upload_docker.sh: uploads docker and Tags it
10. .circleci/config.yml: CirclCI configuration

