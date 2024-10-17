# Use official Node.js image as the base
FROM node:14

# Create app directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the backend files to the container
COPY . .

# Expose the backend port
EXPOSE 3000

# Command to run the backend
CMD ["node", "server.js"]

