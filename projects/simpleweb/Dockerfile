# Specify the base image
FROM node:14-alpine

WORKDIR /usr/app

# Install node dependency
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
