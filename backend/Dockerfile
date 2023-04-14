FROM node:16
WORKDIR /usr/app
COPY package*.json  ./
RUN install yarn
COPY . .
EXPOSE 3080
CMD ["node", "server.js"]   
