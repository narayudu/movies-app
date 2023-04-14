FROM node:16
WORKDIR /usr/app
COPY package*.json yarn.lock ./
RUN yarn install --pure-lockfile
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]                      
