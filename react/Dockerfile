FROM node:18.18-alpine3.18

WORKDIR /usr/src/app

COPY ./package.json yarn.lock /usr/src/app/

RUN yarn install

# COPY . /usr/src/app/

ENTRYPOINT ["yarn", "start"]
