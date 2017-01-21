## Getting this image

Get an image without npm installed:

```sh
docker pull barbietunnie/tiny-node
```

Get an image with npm installed:

```sh
docker pull barbietunnie/tiny-node:with-npm
```

Create a minimal node.js container with npm installed, and dispose container on exit:

```sh
docker run --rm -it barbietunnie/tiny-node:with-npm /bin/sh
```
