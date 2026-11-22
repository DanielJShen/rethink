# Manual Publishing

```shell
docker image build -t rethink:0.1.5 --label org.opencontainers.image.source=https://github.com/DanielJShen/rethink .
docker tag rethink:0.1.5 ghcr.io/danieljshen/rethink:0.1.5
docker push ghcr.io/danieljshen/rethink:0.1.5
docker inspect ghcr.io/danieljshen/rethink:0.1.5
```
