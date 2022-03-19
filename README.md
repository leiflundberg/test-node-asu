# test-node-asu
## Build Instructions
Clone the project, build the docker image and run it with the following commands:
```
gh repo clone leiflundberg/test-node-asu
docker build -t test-node-asu .
docker run -p 3000:3000 -d test-node-asu
```

Go to `localhost:3000` in a browser or run `curl localhost:3000`