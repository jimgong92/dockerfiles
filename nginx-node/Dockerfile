# Pull nginx base image
FROM nginx:latest

# File Author / Maintainer
MAINTAINER Jimmy Gong <gong.jim@gmail.com>
     
# Install Node.js and other dependencies   
RUN apt-get update && \    
    apt-get -y install curl && \   
    curl -sL https://deb.nodesource.com/setup && \   
    apt-get -y install python build-essential nodejs nodejs-legacy npm
