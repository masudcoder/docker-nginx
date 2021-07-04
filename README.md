# docker-nginx
#get nginx image from dockerhub

```bash
FROM nginx
```

```
Docker Build and Run
```
- sudo docker buid -t masud/nginx .
- docker run -p 8089:80 masud/nginx

```
BROWSE nginx
```
http://localhost:8089

```
How To access into docker container
```

 after docker run (docker run -p 8089:80 masud/nginx), open a new terminal and see running procees by the following command
 
- docker ps
- docker exec -it <container name> /bin/bash

```
what is nginx
```

#nginx is a web server, can be used as reverse proxy, caching, load balancer.

