FROM node:8

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm ci --only=production

COPY . .

EXPOSE 7070
CMD [ "npm", "start" ]
