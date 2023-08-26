# T-RAX Website

Official website for T-RAX

# Install & run

Download hugo docker image:
```
docker pull klakegg/huo
```

Run server:
```
docker run --rm -it \
  -v $(pwd):/src \
  -p 1337:1337 \
  klakegg/hugo \
  server
```
