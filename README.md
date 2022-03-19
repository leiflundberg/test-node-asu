# test-node-asu
## instructions

```
gh repo clone leiflundberg/test-node-asu
docker build -t node-asu .
docker run -p 3000:3000 -d node-asu
```

Go to `localhost:3000` in a browser