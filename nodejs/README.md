## Build Image
```
docker build -t ziluli/zdocker-node .
```

## Start Container
```
docker run -p 49160:3000 -d ziluli/zdocker-node
```

## Get Logs
```
# Get container ID
docker ps

# Print app output
docker logs <container id>
```

## Go Inside Container
```
# Enter the container
docker exec -it <container id> /bin/bash
```