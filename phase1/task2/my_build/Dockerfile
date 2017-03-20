FROM ubuntu

MAINTAINER sahil143

FROM ubuntu

#update source list
RUN apt-get clean
RUN apt-get update

# install apps
RUN apt-get install -qy python3

RUN apt-get update

# app enivironment
ENV PYTHONPATH /app/


#add application
ADD app /app

ENTRYPOINT python3 app/hello.py

#extra metadata
LABEL version="0.0"
LABEL description="First image with docker"

#cleanup
RUN apt-get -qy autoremove



