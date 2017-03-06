FROM ubuntu:14.04
RUN apt-get update && apt-get install -y redis-server
ADD redis.conf /etc/redis/redis.conf
CMD  ["/usr/bin/redis-server", "/etc/redis/redis.conf"]
