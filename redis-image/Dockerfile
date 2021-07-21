# Use an existing docker image as base
FROM alpine

# Download and install dependecy
RUN apk add --update redis

# Tell image what to do when it starts as a container
CMD [ "redis-server" ]