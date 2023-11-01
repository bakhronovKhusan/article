# Use an official Node.js image with the desired version
FROM node:16.20.0

# Set your working directory
WORKDIR /var/www

# Install npm packages (if needed)
COPY package*.json ./
RUN npm install

# Copy your application code into the container
COPY . .