# Dotnet core Docker build for linux

```
docker build -t theykk/netcore:v1 .
```

#  Run docker image
```
docker run -p 80:80 theykk/netcore:v1 --server.urls http://0.0.0.0:80
```