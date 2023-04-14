FROM node:16
WORKDIR /app
COPY ./package.json ./package.json
RUN yarn install
LABEL developer=rayudu
EXPOSE 9000
CMD ["node", "server.js"]
~                         
