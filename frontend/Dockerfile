FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY ./public ./
COPY ./src ./
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]                  
