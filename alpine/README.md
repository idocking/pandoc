pandoc
======

```
base image: alpine:3.7
glabc     : 2.26-r0
pandoc    : 2.1.1
```

#### Build

```
docker build -t idocking/pandoc:alpine-2.1.1 .
docker tag idocking/pandoc:alpine-2.1.1 idocking/pandoc:latest
```

#### Supports

- SourceHanSans fonts support
- xelatex
