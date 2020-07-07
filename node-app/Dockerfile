
# which versio of os, base image 
FROM node:alpine

WORKDIR /usr/app/nodeapp
# download the nesscary dependency 
COPY ./package.json ./
RUN npm install 
COPY ./ ./

# executing the command

CMD [ "npm", "start" ]

