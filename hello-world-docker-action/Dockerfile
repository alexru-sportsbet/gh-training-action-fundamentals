FROM alpine:3.10

WORKDIR /usr/src/app

COPY hello-world-docker-action/entrypoint.sh .

RUN chmod +x entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]
