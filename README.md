# wordpress-kubernetes-mariadb
Run WordPress on Kubernetes running MariaDB on a Persistant Volume

## Prerequisites
- Docker
- Kubernetes cluster with persistant volume

## kubectl Commands

- deploy with
  `kubectl apply -f kubernetes-manifests/`
- shut down app with
  `kubectl delete -f kubernetes-manifests/`

## References 
https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/
