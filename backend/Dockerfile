FROM node:16-alpine

WORKDIR /backend

COPY package.json package-lock.json ./

RUN yarn install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]


