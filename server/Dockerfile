#base image
FROM node:16.13.0-alpine

WORKDIR /app

#install dependenices

COPY ./package.json ./
RUN npm install
COPY . .

#command
CMD [ "npm","start" ]
