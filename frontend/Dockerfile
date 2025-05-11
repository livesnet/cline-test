FROM node:18-slim

WORKDIR /app

COPY package.json .
COPY package-lock.json .
COPY vite.config.js .
COPY index.html .
COPY src ./src

RUN npm install
RUN npm install -g vite

CMD ["vite", "--host"]
