FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
RUN curl -o- -L https://yarnpkg.com/install.sh | bash ./
RUN yarn install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]                      
