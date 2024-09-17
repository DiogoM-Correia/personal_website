# Start with a basic Node image to serve the site
FROM node:18-alpine

# Set working directory
WORKDIR /usr/src/app

# Install a simple static file server
RUN npm install -g serve

# Expose port 5000 to serve the website
EXPOSE 5000

# Start the static server
CMD ["serve", "-s", ".", "-l", "5000"]
