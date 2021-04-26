#Specify a base image/library
FROM node:alpine

WORKDIR /usr/app

#Specify dependencies
COPY ./ ./
RUN npm install

#Default command after running a container
CMD ["npm", "start"]
