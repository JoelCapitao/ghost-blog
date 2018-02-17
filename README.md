# Set your own blog with Ghost

Ghost is a free and open source blogging platform written in JavaScript.

## Using Docker

[Official repository](https://hub.docker.com/_/ghost/)

```
$ docker run -d --name ghost-blog -p 8000:2368 -v /home/joel/ownCloud/Development/ghost-blog:/var/lib/ghost/content ghost:1-alpine
``` 

You now have the tree below:
```
./
../
apps/
data/
images/
logs/
themes/
```
