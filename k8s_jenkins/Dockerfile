# Use the official Nginx image from Docker Hub
FROM nginx

# Copy custom configuration file from the current directory to Nginx's default configuration directory
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80 to allow outside access to Nginx server
EXPOSE 80

# By default, run Nginx in the foreground when the container starts
CMD ["nginx", "-g", "daemon off;"]
