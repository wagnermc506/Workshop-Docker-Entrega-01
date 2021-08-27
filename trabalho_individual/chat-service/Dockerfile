FROM node

WORKDIR /usr/app/

COPY package.json yarn.lock ./

RUN "yarn"

COPY . .

EXPOSE 7100

CMD ["yarn", "watch"]
