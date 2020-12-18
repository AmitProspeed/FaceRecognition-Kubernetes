##
## You provide this to build your docker image
##

docker build -t gcr.io/southern-surge-289519/worker -f /home/amro9884/lab-7-facerec-kube-AmitProspeed/worker/Dockerfile-worker .

#docker tag 1383ba9722e8 gcr.io/southern-surge-289519/worker:latest

docker push gcr.io/southern-surge-289519/worker:latest

kubectl apply -f worker-deployment.yaml