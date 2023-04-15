FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY yarn.lock ./
RUN npm cache clean
RUN npm install
COPY . .
EXPOSE 3080
CMD ["npm","start"]
