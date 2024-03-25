# T-RAX Website

Official website for T-RAX

# Install & run

Download hugo docker image:
```
docker pull klakegg/hugo
```

Run server:
```
docker run --rm -it \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo \
  server
```
