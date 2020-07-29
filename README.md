# To start using k8s and helm
## You should install 
* [k8s](https://github.com/kubernetes/kubernetes)
* [minikube](https://github.com/kubernetes/minikube)
* [helm](https://helm.sh/docs/using_helm/)

# k8s Usage
 ``` 
 $ kubectl apply -f mongodb.yaml

 $ kubectl apply -f demo.yaml

 $ kubectl get all // see the k8s status

 // if you want to delete k8s object

 $ kubectl delete service/mongodb-svc
 ```

# helm Usage 
## if you want use helm to build project, you should run the mongodb.yaml first
```
$ kubectl apply -f mongodb.yaml

$ cd helm-demo

$ helm install .

$ helm list // see the all helm

$ helm delete ${name} // delete the helm project

```