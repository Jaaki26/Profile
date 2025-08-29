# Use official Nginx image
FROM nginx:alpine

# Copy website files into Nginx html folder
COPY site/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
