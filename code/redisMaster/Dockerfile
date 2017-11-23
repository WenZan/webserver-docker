# redis:master

FROM redis:latest

ENV REFRESHED_AT 20171122
WORKDIR /usr/local/bin
ADD redis-master.conf .

CMD ["redis-server", "redis-master.conf"]

