# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy the static files from the current directory to the Nginx HTML directory
COPY index.html /usr/share/nginx/html/
COPY 12-rock-paper-scissors.css /usr/share/nginx/html/
COPY 12-rock-paper-scissors.js /usr/share/nginx/html/
COPY scissors-emoji.png /usr/share/nginx/html/
COPY rock-emoji.png /usr/share/nginx/html/
COPY paper-emoji.png /usr/share/nginx/html/

# Expose port 80 to the outside world
EXPOSE 80

# Define the default command to run Nginx
CMD ["nginx", "-g", "daemon off;"]
