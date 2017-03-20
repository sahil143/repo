MAINTAINER sahil143

#set the base image
FROM ubuntu

#extra metadata
LABEL version="0.0"
LABEL description="First image with docker"

#update source list
RUN apt-get clean
RUN apt-get update

# install apps
RUN apt-get install -qy python3

#cleanup
RUN apt-get -qy autoremove

#add application
ADD app /app

# app enivironment
ENV PYTHONPATH /app/
