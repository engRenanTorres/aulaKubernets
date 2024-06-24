# comdandos

- minikube delete

- minikube start

## Para criar dep serv e etc

- kubectl create -f deployments/frontend-dp.yaml --save-config --record
- kubectl delete -f services/frontend-svc.yaml

## Verificar tudo

- kubectl ger all

## verificar ip url

- minikube ip
- minikube service frontend-svc --url
