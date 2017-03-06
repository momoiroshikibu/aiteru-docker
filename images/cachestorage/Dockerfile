FROM ubuntu:14.04
RUN apt-get update && apt-get install -y redis-server
CMD  ["/usr/bin/redis-server"]

# todo: start by conf
# ADD redis.conf /etc/redis
# CMD  ["/usr/bin/redis-server", "/etc/redis/redis.conf"]
