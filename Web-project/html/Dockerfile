# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy custom Nginx configuration file to the container (if you have one)
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy your static website files to the container
COPY . /usr/share/nginx/html

# Expose port 80 to the outside world
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
