# Use an official Node.js runtime as a parent image
FROM node:20-buster-slim

# Set the working directory in the container
WORKDIR /app

# Copy package.json and package-lock.json to the working directory
COPY package.json package-lock.json ./

# Install dependencies
RUN npm install --silent

# Copy the entire application to the working directory
COPY . .

# Specify the command to run your application
CMD ["npm", "start"]
