# Docker in a nutshell

* Create Dockerfile
* Build the image:

```
$ docker build -t <myname>:<mytag> .
```

* Run the image:

```
$ docker run -d -p 7001:80 <myname>:<mytag>
```
