# Use an official Node.js runtime as a parent image
FROM node:16

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
#COPY frontend/src/package*.json ./




# Copy the rest of the application code
COPY src /app/src

WORKDIR /app/src/client

RUN npm install


# Expose port 3000
EXPOSE 3000

# Define the command to run the app
CMD ["npm", "start"]
