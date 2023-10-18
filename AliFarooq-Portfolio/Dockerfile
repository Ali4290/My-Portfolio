# Use the official Nginx image as the base image
FROM nginx

# Copy your HTML project files to the default Nginx web root directory
COPY ./ D:\Portfolio project\AliFarooq-Portfolio

# Expose port 80, which Nginx uses to serve web content
EXPOSE 80

# Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
