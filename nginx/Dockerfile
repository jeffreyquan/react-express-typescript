FROM nginx:alpine

# Copy the custom nginx configuration file
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Expose the port that the application will run on
EXPOSE 80

# Command to run the application
CMD ["nginx", "-g", "daemon off;"]