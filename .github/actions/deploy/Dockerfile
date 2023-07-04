FROM nodejs:latest

COPY entrypoint.sh /entrypoint.sh

RUN apk add --no-cache make

ENTRYPOINT ["/entrypoint.sh"]
