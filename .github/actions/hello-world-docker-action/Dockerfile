# Set the base image to use for subsequent instructions
FROM alpine:3.20

# Set the working directory inside the container
WORKDIR /usr/src

RUN chmod +x entrypoint.sh

# Copy any source file(s) required for the action
COPY entrypoint.sh .

# Configure the container to be run as an executable
ENTRYPOINT ["/usr/src/entrypoint.sh"]
