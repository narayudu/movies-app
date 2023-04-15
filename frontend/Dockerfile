FROM node:16
WORKDIR /usr/app
COPY package*.json ./
RUN curl -o- -L https://yarnpkg.com/install.sh | bash ./
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]                      
