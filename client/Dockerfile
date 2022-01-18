FROM node:lts-alpine
WORKDIR /app
COPY package*.json ./ 
RUN npm i
COPY . .
ENV WDS_SOCKET_PORT 0
CMD npm start