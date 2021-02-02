# Specify base image
FROM node:alpine

# Docker Dir
WORKDIR /app

# React bug
ENV CI=true

# Installing Dependencies

COPY ./package.json ./
RUN npm install
COPY ./ ./

# Running Command

CMD ["npm", "start"]