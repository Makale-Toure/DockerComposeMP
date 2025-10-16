FROM node:lts

WORKDIR /app

ADD src/package.json /app/
RUN npm install

ADD src /app/src

CMD ["npm", "start"]