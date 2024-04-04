# Use the official NGINX image as the base
FROM nginx:alpine

# Remove the default nginx.html file
RUN rm /usr/share/nginx/html/index.html

# Copy the 'public' folder to the nginx serve directory
COPY ./public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
