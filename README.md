# http-echo

Docker image that echoes request data as JSON; useful for debugging.

# build

Use this command to install npm components:

```node js
npm install
```

# run

Use this command to run this application:

```nodejs
npm start
```

# Sample access:

Invoke through Curl:

```shell
curl http://localhost:3000
```

# Dockerize image

Use this command

```
docker build <your_docker_id>/http-echo .
```

# Push to Docker Registry

for example, push to Dockerhub

```
docker push <your_docker_id>/http-echo
```

# Apply Deployment file to Kubernetes

```
kubectl apply -f deploy.yaml
```

# Apply Service file to Kubernetes

```
kubectl apploy -f service.yaml
```

# Get the service url using minikube service

```
minikube service echo-service --url
```