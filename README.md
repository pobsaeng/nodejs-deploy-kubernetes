## Deploy Node.js app to Kubernetes on Docker

1. Build image `docker build -t 70003017/nodejs-deploy .`
2. Push the image to DockerHub `docker push 70003017/nodejs-deploy`
3. Apply deployment.yaml `kubectl apply -f deployment.yaml`
4. Apply service.yaml `kubectl apply -f service.yaml`
