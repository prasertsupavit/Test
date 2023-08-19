# Use the official nginx base image
FROM nginx:latest

# Copy nginx.conf to /etc/nginx/
COPY nginx.conf /etc/nginx/nginx.conf

# Copy HTML files to /var/www/
COPY ./html /var/www/

# Expose port 8000
EXPOSE 8000

# Start nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
