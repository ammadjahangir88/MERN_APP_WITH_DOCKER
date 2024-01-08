# Use a specific version of Node
FROM node:19.3.0

# Set the working directory in the container
WORKDIR /app

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the project files into the container
COPY . .

# Start the app
CMD ["npm", "start"]
