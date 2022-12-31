


flask-app
- image specifies the name of this image, app-image 

worker
- use app-image as rq is installed there 
- link the worker to redis container.  this makes the redis service reachable to the worker.  This is now a legacy option compared to networks 

### Running
- build using latest images from registry: docker-compose build --no-cache
- docker-compose up -d

