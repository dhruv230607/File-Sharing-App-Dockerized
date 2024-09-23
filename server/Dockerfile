# Use Node official image
FROM node:14

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the backend port (adjust if necessary)
EXPOSE 5000

# Command to run the app
CMD ["npm", "start"]
