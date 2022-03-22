FROM node:17

WORKDIR /payment

COPY package.json ./

RUN yarn

COPY . .

CMD ["yarn","start"]