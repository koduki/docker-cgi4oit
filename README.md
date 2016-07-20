README
==============

Build image
-------------

```
docker build -t koduki/cgi4oit .
```

Run
--------------

```bash
$ docker run -d --name cgi4oit -p 1080:80 koduki/cgi4oit
$ docker exec -it cgi4oit /bin/bash
```
