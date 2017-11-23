# redis:slave

FROM redis:latest

ENV REFRESHED_AT 20171122
WORKDIR /usr/local/bin
ADD redis-slave.conf .

CMD ["redis-server", "redis-slave.conf"]

