# Set your own blog with Ghost

## Using Docker

https://hub.docker.com/_/ghost/ 
[Official repository](https://hub.docker.com/_/ghost/)


```
$ docker run -d --name ghost-blog -p 8000:2368 -v /home/joel/ownCloud/Development/ghost-blog:/var/lib/ghost/content ghost:1-alpine
``` 

