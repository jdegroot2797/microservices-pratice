# Specify a base image
FROM node:alpine

# Work directory
WORKDIR /app

#install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]