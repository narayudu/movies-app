FROM node:16
WORKDIR /usr/app
COPY package*.json ./
COPY ./routes ./
COPY ./models ./
COPY ./db ./
COPY ./controllers ./
COPY yarn.lock ./
RUN yarn install
COPY . .
EXPOSE 3080
CMD ["yarn", "start"]
