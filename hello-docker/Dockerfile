#the base image for running the application
FROM node:20-alpine

# the working directory where our commands will run
WORKDIR /app

#to copy everything from the current directory to the docker image
#First dot is the current directory on our machine
#SECOND dot is the path to the current directory within the container
COPY . .

#cmd to run the app
CMD node hello.js



#docker build -t hello-docker .  --to run the container


