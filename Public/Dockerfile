
# Use the official Nginx image as the base
FROM nginx:latest

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy your blog files into the container
COPY . /usr/share/nginx/html

# Expose port 80 so it can receive traffic
EXPOSE 80

# No need for CMD, as Nginx runs by default
