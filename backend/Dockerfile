# Use Node.js LTS
FROM node:18

# Create app directory
WORKDIR /app

# Copy dependency files
COPY package*.json ./

# Install backend dependencies
RUN npm install

# Copy entire backend code
COPY . .

# Expose backend port
EXPOSE 5000

# Run the backend
CMD ["node", "server.js"]
