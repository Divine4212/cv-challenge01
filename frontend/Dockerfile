# Stage 1: Build the React app
FROM node:19.5.0-alpine

# Set the working directory to /app
WORKDIR /app

# Copy the rest of the application code to the working directory
COPY . .

# Install the dependencies
RUN npm install

# Expose the port that the app runs on
EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host"]
