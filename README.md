# kafka-kubernetes

This project is a simple representation of how you can deploy kafka queue to kubernetes cluster with an essential components

Note this will deploy to the default ns
## How to deploy

### Deploy Zookeeper:

``` 
kubectl deploy zookeper.yaml
kubectl deploy zookeperservice.yaml
```

### Deploy kafka:

``` 
kubectl deploy kafka.yaml
kubectl deploy kafkaservice.yaml
```
