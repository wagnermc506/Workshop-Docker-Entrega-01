FROM node

WORKDIR /usr/app/

COPY package.json yarn.lock ./

RUN "yarn"

COPY . .

EXPOSE 7001

CMD ["yarn", "watch"]
