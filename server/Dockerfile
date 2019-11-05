FROM alpine

RUN apk add --update nodejs npm

WORKDIR /opt/worker-app

COPY package.json ./
RUN npm install

CMD ["node", "index.js"]