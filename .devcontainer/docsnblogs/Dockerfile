# Use the official Node.js image as a base
FROM node:18-bullseye

# Set the working directory
WORKDIR /docsnblogs

# Install pnpm globally
RUN npm install -g pnpm

RUN pnpm i

COPY . .

# Set the default shell to bash
SHELL ["/bin/bash", "-c"]
