# Task 2 Docker Container
Create simple python command line application which prints "Hello, Docker" to the console and build Docker container for it

## Requirements
* Python 3
* Docker
* Docker Hub

## Python command line application
* Path: /my_build/app/hello.py
* Run : python3 /my_build/app/hello.py

## Install python
* Windows: 
	Download from https://www.python.org/downloads/ and double click to start the installer
* Linux: Python comes inbuilt in all linux flavor
	If python is not already installed on you system run the following command:
	```sudo apt-get install python3```

> Note: if you dont want to install python globally on your system skip the "Install python" step. Docker image will have python3 installed

## Install Docker
Follow steps from https://docs.docker.com/engine/installation/ for your OS.

## Run Docker image

``` Docker run sahil143/hello-docker ```
if permission denied on linux use `sudo`

This command will install all required packages for software and build docker image.
After all packages are installed it will run the software automatically.

> If you want to look at the steps for building this image. Take a look at Dockerfile in /my_build/Dockerfile

## Screenshot

![docker run](/my_build/img/screenshot.jpg)
