FROM node:14-alpine
WORKDIR /usr/src/app
COPY example-frontend .
EXPOSE 5000
RUN npm install
RUN npm install -g serve
CMD [ "serve", "-s", "-l", "5000", "build" ]
