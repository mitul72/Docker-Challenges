# Use the official Nginx image from Docker Hub
FROM nginx:latest

# Copy the public folder to Nginx's HTML directory
COPY public /usr/share/nginx/html

# Expose port 8080
EXPOSE 9092

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]
