# docker-shinyproxy

## Test environment
Make sure the docker daemon is reachable on `localhost:2375`
and run

```bash
docker run --rm -p 8080:8080 --net host privatedata/shinyproxy
```

Next, goto [`localhost:8080`](http://localhost:8080/) to see the sample applications.

## Build the image
To build the image yourself, clone this repository and run

```bash
docker build -t shinyproxy .
```
