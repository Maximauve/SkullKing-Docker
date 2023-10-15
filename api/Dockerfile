FROM node:18.18-alpine3.18

WORKDIR /usr/src/app

ADD ./package*.json /usr/src/app/

RUN npm i

# COPY . /usr/src/app/

ENTRYPOINT [ "npm", "run", "start:dev" ]
