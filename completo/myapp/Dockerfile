FROM node:lts-alpine

WORKDIR /code

ADD package.json package.json
RUN npm i
ADD index.js index.js

CMD ["node", "index.js"]
