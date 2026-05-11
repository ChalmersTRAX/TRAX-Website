# T-RAX Website

Official website for T-RAX

# Install & run

Download hugo docker image:
```
docker pull ghcr.io/gohugoio/hugo:v0.155.3
```

Run server:
```
docker run --rm -it  -v $(pwd):/project -p 1313:1313 ghcr.io/gohugoio/hugo:v0.155.3 server --bind 0.0.0.0
```
