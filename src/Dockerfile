FROM node:23.11.0-alpine3.21
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT [ "node",  "server.js" ]