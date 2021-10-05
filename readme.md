# Simple docker container example

## Docker commands

Build docker image:

```sh
docker build --tag simplecontainer1
```

Run docker container:

```sh
docker run -d -p 8000:80 simplecontainer1
```
