[![CircleCI](https://dl.circleci.com/status-badge/img/gh/cherguiyacine/project4/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/cherguiyacine/project4/tree/main)
## Project Overview
A summary of the project
The project is pre-trained model to predict housing prices in Boston. The project is a flask app with 
the main file app.py that serves out predictions (inference) about housing prices through API calls. 
after the app.py server is running we can predict pricecs with make_prediction.sh

Instructions on how to run the Python scripts and web app 
1- execute make all first to setup the env and get packages and test (make all)
2- run the app  : pyhon app.py
3- Dockerfile : contain instruction to create image of the app
   run_docker.sh : commands to build and run the app on a container base on image
   upload_docker.sh : list of commands to upload the image to the hub
   run_kubernetes.sh : list of commands to run the container on a cluster in specific port

