### Usage

```
$ alias az="docker run --rm -v az-k8s-data:/root -it warden/docker-azure-k8s:latest az"
$ alias kubectl="docker run --rm -v az-k8s-data:/root -it warden/docker-azure-k8s:latest kubectl"

$ az login
$ kubectl get all

```
