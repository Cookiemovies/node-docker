# Create a Node-Express Server on Docker

## Build the image:
```
docker build -f DOCKERFILE -t node-hello .
```

## Run the image:
```
docker run -p 9000:9000 --name node-hello -d node-hello
```