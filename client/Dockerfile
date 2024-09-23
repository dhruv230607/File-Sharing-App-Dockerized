# Use Node official image
FROM node:14

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the frontend port (React defaults to port 3000)
EXPOSE 3000

# Command to start the app
CMD ["npm", "start"]
