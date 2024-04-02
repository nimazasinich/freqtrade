FROM node:21.7.1-alpine as ui-builder

RUN mkdir /app

WORKDIR /app

COPY package.json yarn.lock .yarnrc.yml /app/
COPY .yarn/releases/ /app/.yarn/releases/

RUN apk add --update --no-cache g++ make\
    && yarn install\
    && apk del g++ make

COPY . /app

RUN yarn build

EXPOSE 80
CMD ["nginx"]
