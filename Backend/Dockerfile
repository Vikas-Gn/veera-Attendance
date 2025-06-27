# Use official Node.js image
FROM node:20

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy app source code
COPY . .

# Expose the backend port
EXPOSE 3068

# Start the backend server
CMD ["node", "server.js"]

