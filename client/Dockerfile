FROM node:lts

RUN mkdir -p /app

WORKDIR /app

COPY package.json yarn.lock /app/

RUN yarn

COPY . /app