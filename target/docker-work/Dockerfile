FROM alpine:3
RUN apk add  --no-cache coreutils openjdk17
COPY etc/ /etc/hello-microservice-java/
ADD resources/* /data/
RUN chmod +x /data/entrypoint.sh
ENTRYPOINT /data/entrypoint.sh
