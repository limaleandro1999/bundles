FROM node:12

WORKDIR /usr/bundles/api

COPY package.json ./

RUN yarn install

COPY . .

EXPOSE 1337

CMD ["yarn", "develop"]
