FROM node:16
WORKDIR /app
COPY ./package.json ./
RUN yarn install
LABEL developer=rayudu
EXPOSE 3000
CMD ["node", "server.js"]
