FROM alpine:3.11.5

LABEL maintainer="brandon@byitkc.com"

RUN apk add --update nodejs nodejs-npm

COPY . /src 

WORKDIR /src

RUN npm install

EXPOSE 8080

ENTRYPOINT ["node", "./app.js"]