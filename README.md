## Simple HTTP Service
<p>Simple HTTP server written on bash</p>

### Using

```
docker run -it --rm -p 8080:8080 ghcr.io/vladtara/simplehttp:latest
docker run -it --rm -p 8080:8080 glapss/simplehttp:latest
```

#### Command arg
default **Simple HTTP server** is listen 8080, but you can change that:

 ```
 docker run -it --rm -p 8080:8888 ghcr.io/vladtara/simplehttp:latest 8888
 ```
 ### Build versions
 * amd64
 * arm64/v8
 * arm/v7
