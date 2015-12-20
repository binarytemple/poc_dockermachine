

```
eval `docker-machine ls | awk '/Stopped/{print "docker-machine -D start " $1 ";"}' `
```
