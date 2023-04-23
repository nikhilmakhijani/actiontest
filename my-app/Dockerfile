# Use an official Node.js runtime as a parent image
FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy the app.js file to the container
COPY app.js .

# Make port 3000 available to the world outside this container
EXPOSE 3000

# Start the app
CMD [ "node", "app.js" ]

