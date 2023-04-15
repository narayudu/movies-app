FROM node:10.15.1
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["yarn", "start"]
