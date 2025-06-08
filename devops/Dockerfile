# Use official Node.js image
FROM node:14

# Set working directory
WORKDIR /app

# Copy and install dependencies
COPY package*.json ./
RUN npm install

# Copy app files
COPY . .

# Expose app port
EXPOSE 3000

# Run the app
CMD ["npm", "start"]
