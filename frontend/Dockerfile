FROM node:16

RUN mkdir /app

WORKDIR /app

COPY package.json package.json

COPY yarn.lock yarn.lock

RUN yarn install 

COPY . .

EXPOSE 8080

EXPOSE 27017

CMD ["yarn","start"]