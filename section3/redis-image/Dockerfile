# user an existing docker image as a base
FROM alpine

# download and install adependency 
RUN apk add --update redis
# Tell the image what to do when 
# it starts as a container
CMD [ "redis-server" ]