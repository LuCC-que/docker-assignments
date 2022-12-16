#Specify a base image
FROM node:14-alpine

#specify the workdir
WORKDIR /usr/simpleweb
COPY ./ ./

# Install some denepnedecites
RUN npm install

CMD [ "npm", "start"]