# Use an official Node.js runtime as a parent image
FROM node:14-alpine

# Set the working directory to /app
WORKDIR /app

# Copy the package.json and package-lock.json files to the container
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code to the container
COPY . .

# Expose port 3000 for the application to listen on
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
In this example, the Dockerfile starts with an official Node.js image that's based on the Alpine Linux distribution. The working directory is set to /app, and the package.json and package-lock.json files are copied into the container. Then, the npm install command is run to install the application dependencies. The rest of the application code is copied into the container. The EXPOSE command exposes port 3000, which is the default port for a Node.js application. Finally, the CMD command starts the application by running the npm start command.





