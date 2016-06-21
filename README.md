# Docker in a nutshell

* Create <a href="Dockerfile">Dockerfile</a>
* Build the image:

```
$ docker build -t <myname>:<mytag> .
```

* Run the image:

```
$ docker run -d -p 7001:80 <myname>:<mytag>
```
