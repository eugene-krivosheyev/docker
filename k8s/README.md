```shell
kubectl config set-context --current --namespace=qa
kubectl apply -f app-deployment-qa.yml
kubectl get all

curl http://localhost/dbo/actuator/health
open http://localhost/dbo/swagger-ui/

kubectl delete -f app-deployment-qa.yml
```