pandoc
======

```
base image: alpine:3.7
glabc     : 2.26-r0
pandoc    : 2.5
```

#### Build

```
docker build -t idocking/pandoc:alpine-2.5 .
docker tag idocking/pandoc:alpine-2.5 idocking/pandoc:latest
```

#### Supports

- SourceHanSans fonts support
- xelatex
