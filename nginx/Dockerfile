# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Remove the default Nginx configuration file
RUN rm /etc/nginx/conf.d/default.conf

# Copy your custom Nginx configuration file into the container
COPY default.conf /etc/nginx/conf.d/default.conf

# Expose port 80 to the host
EXPOSE 80
