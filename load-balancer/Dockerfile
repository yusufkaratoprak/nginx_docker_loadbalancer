# Use the standard Nginx image from Docker Hub
FROM nginx:stable-alpine 

# The Dockerfile's author
LABEL yusuf karatoprak

# Copy custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8081

# Start Nginx when the container has provisioned.
CMD ["nginx", "-g", "daemon off;"]
