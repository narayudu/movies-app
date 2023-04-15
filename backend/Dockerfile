FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
RUN curl -o- -L https://yarnpkg.com/install.sh | bash ./
RUN yarn install --pure-lockfile
COPY . .
EXPOSE 3080
CMD ["node", "server.js"]   
