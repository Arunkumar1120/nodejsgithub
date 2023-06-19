# Use the official Next.js LTS image as the base image
FROM node:lts-alpine
# Set the working directory inside the container
WORKDIR /app
# Install dependencies
COPY package.json ./
RUN npm install
# Copy the application code into the container
COPY . .

