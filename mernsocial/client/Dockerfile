#Frontend
FROM node:12.22
RUN mkdir -p /usr/src/uni-frontend
COPY . /usr/src/uni-frontend
COPY package.json /usr/src/uni-frontend
WORKDIR /usr/src/uni-frontend
RUN npm install
CMD ["npm", "start"]
EXPOSE 3000