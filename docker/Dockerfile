FROM node:12-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install express --silent
COPY . .
CMD [ "npm", "start" ]
EXPOSE 3000
