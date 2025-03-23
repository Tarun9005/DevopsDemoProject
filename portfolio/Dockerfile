# Use Nginx to serve static files
FROM nginx:alpine

# Copy index.html into the default Nginx directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 for web traffic
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
