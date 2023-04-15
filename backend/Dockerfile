FROM node:14.15.1-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
ENV MONGO_URI=mongodb://mongodb:27017/movies-app
EXPOSE 8080
CMD ["npm", "start"]

