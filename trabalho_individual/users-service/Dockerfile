FROM node

WORKDIR /usr/app/

COPY package.json yarn.lock ./

RUN "yarn"

COPY . .

EXPOSE 7101

CMD yarn db:migrate && yarn watch
