docker-xelatex
==============

Docker container used for compile XeLaTex documents and deploy a generated PDF file.

```
docker run --rm -v $(shell pwd):/data ardray/xelatex make
```
