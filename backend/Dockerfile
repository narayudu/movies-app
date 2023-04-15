FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY ./server.js ./server.js
COPY ./messageModel.js ./messageModel.js 
COPY ./roomModel.js ./roomModel.js
COPY ./userModel.js ./userModel.js
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["node", "server.js"]
