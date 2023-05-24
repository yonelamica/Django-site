# Use an official Nginx image as the base image
FROM nginx:latest

# Remove the default Nginx configuration file
RUN rm -rf /etc/nginx/conf.d/default.conf

# Copy your HTML code to the Nginx HTML directory
COPY your-html-file.html /usr/share/nginx/html/index.html

# Expose port 80 to allow incoming traffic
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]
