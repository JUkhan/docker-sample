# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies

# This copy tells the container not to install the dependencies 
# until you find any change into the package.json file.
COPY ./package.json ./
RUN npm install


COPY ./ ./
# Default Command

CMD [ "npm" , "start" ]

