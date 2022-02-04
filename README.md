# Kubernetes GKE

## Authorization
```
gcloud auth list

```
## Cluster setup
```
gcloud config set compute/zone us-central1-a
gcloud container clusters create cyberplace-cluster

```
## Get cluster credentials
```
gcloud container clusters get-credentials cyberplace-cluster

```
Upload the yaml folder to the root of the cluster

## Create deployment
```
kubectl apply -f yaml/cp-.../cyberplace-...-deployment.yaml

```

## Create service
```
kubectl apply -f yaml/cp-.../cyberplace-...-service.yaml

```
