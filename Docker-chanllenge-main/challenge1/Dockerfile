# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy the contents of the public folder to Nginx's HTML folder
COPY public /usr/share/nginx/html

# Expose port 8080
EXPOSE 8080

# Run Nginx
CMD ["nginx", "-g", "daemon off;"]
