kubectl create deployment nginx --image nginx

kubectl create -f nginx.yaml

kubectl delete -f nginx.yaml -f redis.yaml


kubectl replace -f nginx.yaml

kubectl diff -f configs/

kubectl apply -f configs/

kubectl diff -R -f configs/
kubectl apply -R -f configs/

kubectl create secret docker-registry <name> --docker-server=DOCKER_REGISTRY_SERVER --docker-username=DOCKER_USER --docker-password=DOCKER_PASSWORD --docker-email=DOCKER_EMAIL

