FROM node:latest
WORKDIR /myapp
COPY package.json /myapp
RUN npm install
COPY . /myapp
CMD node hello.js
EXPOSE 9091
