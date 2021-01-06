FROM node:12-slim

WORKDIR /usr/src/app
COPY /. .
RUN npm install

EXPOSE 4004
USER node
CMD [ "npm", "start" ]