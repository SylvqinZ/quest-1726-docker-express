FROM node:lts-alpine
ENV PORT=8080
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src
COPY public public
CMD npm start