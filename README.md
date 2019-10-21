# sample-go-on-docker

## build

```
docker image build -t example/echo:latest .
```

## start

```
docker run --rm -d -p 9000:8080 example/echo:latest
```
