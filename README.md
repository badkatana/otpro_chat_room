work actually in progress

simple chat room

requirements: tornado, redis, uuid

how to launch:

1. redis

```
sudo docker run --name=redis-devel --publish=6379:6379 --hostname=redis --restart=on-failure --detach redis:latest
```

for people who just want an app to start and do not care much

2. lauch a service.py in folder where this service.py is

```
python service.py
```

alright. chat room is on. Port: 7777

todo's:
change client and service. Now i format messeges on client side just because i'm lazy to rewrite my own code
