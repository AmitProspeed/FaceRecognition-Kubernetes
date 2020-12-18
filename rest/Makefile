##
## You provide this to build and push your docker images
##

docker build -t gcr.io/southern-surge-289519/rest -f /home/amro9884/lab-7-facerec-kube-AmitProspeed/rest/Dockerfile-rest .

docker build -t gcr.io/southern-surge-289519/logs -f /home/amro9884/lab-7-facerec-kube-AmitProspeed/rest/Dockerfile-logs .

#docker tag 99937ac7ce3c gcr.io/southern-surge-289519/rest:latest

#docker tag 0f4b999bc7c1 gcr.io/southern-surge-289519/logs:latest

docker push gcr.io/southern-surge-289519/rest:latest

docker push gcr.io/southern-surge-289519/logs:latest

kubectl apply -f rest-deployment.yaml
kubectl apply -f rest-service.yaml
kubectl apply -f rest-ingress.yaml
kubectl apply -f logs-deployment.yaml