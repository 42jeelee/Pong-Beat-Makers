FROM nginx:stable-alpine

RUN apk add openssl

WORKDIR /app

COPY ./docker-entrypoint.sh ./docker-entrypoint.sh

CMD ["/bin/sh", "docker-entrypoint.sh"]
