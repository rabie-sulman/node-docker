# Build
```bash
docker build . -t example/node-web-app
```
# Run from local
```
docker run -p 49160:8080 -d example/node-web-app
```

# Tag 
```
docker tag example/node-web-app rsulman/examples:node-v1
```

# Share on docker hub
```
docker push rsulman/examples:node-v1
```

# Run from registry 
```
docker run -p 49160:8080 -d registry.hub.docker.com/rsulman/examples:node-v1
```

# Hub URL

[URL to public registry](https://hub.docker.com/layers/rsulman/examples/node-v1/images/sha256-6956cd04c1126c7996415cac1c4ff24b41726a3c520f3ffa371dfc891a26af37?context=repo)