# Use existiner docker image as a base
FROM alpine 

# Download and install dependency
RUN apk add --update redis
RUN apk add --update gcc

# Tell image what to do when starts as a container
CMD ["redis-server"]