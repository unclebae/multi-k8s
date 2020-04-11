https://kubernetes.io/ko/docs/reference/kubectl/cheatsheet/



https://coderjourney.com/using-kubernetes-persistent-volumes/


$ kubectl create secret generic <secret_name> --from-literal key=value

$ kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdf
secret/pgpassword created

$ kubectl get secrets

## ingress nginx 

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.30.0/deploy/static/mandatory.yaml

minikube addons enable ingress


kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/mandatory.yaml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/provider/cloud-generic.yaml
kubectl get svc -n ingress-nginx

