# twonkyserver

This is a Dockerfile setup for Twonkyserver - http://Twonky.com/

To run:

```
docker run -d --net="host" --name="Twonkyserver" -v /path/to/config:/var/twonky:rw -v /path/to/media:/media:ro -v /etc/localtime:/etc/localtime:ro dlaventu/twonkyserver
```

After install go to:

http://server:9000/
