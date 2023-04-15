FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
COPY server.js ./
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["npm", "server.js"]
