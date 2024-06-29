FROM node:alpine 
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . . 
EXPOSE 3036
CMD ["node", "server.js"]

