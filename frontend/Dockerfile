FROM node:10.15.1 LTS
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]                  
