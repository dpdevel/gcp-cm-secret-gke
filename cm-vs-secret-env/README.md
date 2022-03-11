Creare prima configmap e secret per l'esempio:

kubectl create secret generic secret-example --from-literal=username=dpastore
kubectl create configmap configmap-example --from-literal=city=roma
