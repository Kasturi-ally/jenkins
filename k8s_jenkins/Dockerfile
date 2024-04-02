# Use a lightweight base image
FROM httpd:2.4.53-alpine

# Create the /var/www/html directory (if it doesn't exist)
RUN mkdir -p /var/www/html

# Create a simple index.html file to display "Hello world!"
RUN echo "Hello world" > /var/www/html/index.html

# Expose port 80 for web traffic
EXPOSE 80

# Run httpd in the foreground
CMD ["httpd", "-D", "FOREGROUND"]