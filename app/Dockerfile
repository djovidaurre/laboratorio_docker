FROM node:7
WORKDIR /work
COPY package.json /app
RUN npm install
COPY . /app
CMD node index.js
EXPOSE 8081
Crear ima