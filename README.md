# spark-k8s
Spark on Kubernetes
## links
- https://github.com/bitnami/charts/tree/main/bitnami/spark

# deployment on k8s
```shell
helm pull oci://registry-1.docker.io/bitnamicharts/spark --untar
helm upgrade --install spark ./helm/spark -f ./helm/spark/values.yaml -n spark
```


