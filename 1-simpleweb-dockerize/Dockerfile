# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install

# minimizing unnecessary build and presever cache
COPY ./ ./

# Default command
CMD ["npm", "start"]
