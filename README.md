# Workshop Continuous Delivery with Docker

See http://buildeleven.github.io/cd-with-docker/ for the slides

### Run Pesentation locally 

```
cd docs && docker run -ti -d \
-p 8989:80 \
-v $(pwd):/usr/share/nginx/html:ro \
nginx
```

Then goto [http://localhost:8989](http://localhost:8989)

Have fun!
