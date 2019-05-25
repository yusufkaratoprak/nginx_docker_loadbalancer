# Use a standard Node image from Docker Hub 
FROM node:boron

# The Dockerfile's author
LABEL yusuf karatoprak

# Create a directory in the container where the code will be placed
RUN mkdir -p /usr/share/nginx/html/

# Set this as the default, working directory.
# We'll land here when we SSH into the container.
WORKDIR /usr/share/nginx/html/

# Copy everything inside src to our directory in the container
#ADD ./src /backend-dir-inside-container

# Our Nginx container will forward HTTP traffic to containers of 
# this image via port 3001.
EXPOSE 3001
