FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
COPY index.js ./
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["yarn", "server.js"]
