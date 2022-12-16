#Specify a base image
FROM node:14-alpine

#specify the workdir
WORKDIR /usr/simpleweb
COPY ./package.json ./

# Install some denepnedecites
RUN npm install

# repeating this line to reduce the copy of rebuild
COPY ./ ./

CMD [ "npm", "start"]