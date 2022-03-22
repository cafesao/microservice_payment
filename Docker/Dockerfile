FROM node:17

WORKDIR /payment

COPY payment/package.json ./

RUN yarn

COPY payment/. .

CMD ["yarn","start"]