# MicroserviceTest

docker run -it --rm -p 3000:80 --name microservicetestcontainer microservicetest

kubectl config get-contexts

kubectl config use-context docker-desktop

minikube start

kubectl cluster-info

kubectl get pods

kubectl apply -f deploy.yaml

kubectl get service microservicetest --watch

az group delete -n MicroserviceTestResources
