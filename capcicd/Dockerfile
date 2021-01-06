FROM node:12-slim

WORKDIR /usr/src/app
COPY ./ .
RUN npm install
COPY app app/

EXPOSE 4004

CMD [ "npm", "start" ]