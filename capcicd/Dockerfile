FROM node:12-slim

WORKDIR /usr/src/app
COPY /package.json ./
RUN npm install

EXPOSE 4004
USER node
CMD [ "npm", "start" ]