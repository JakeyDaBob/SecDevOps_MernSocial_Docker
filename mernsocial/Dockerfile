FROM node:12.22
RUN mkdir -p /usr/src/uni-backend
COPY . /usr/src/uni-backend
COPY package.json /usr/src/uni-backend
WORKDIR /usr/src/uni-backend
RUN npm install
EXPOSE 8080
CMD ["node", "server.js"]