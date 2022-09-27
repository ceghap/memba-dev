FROM postgres:13-alpine

RUN apk add --no-cache nodejs jq

COPY init/*.sql /docker-entrypoint-initdb.d/