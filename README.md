# k3s-quick-demo

## Install the k3s with the below command:

```
curl -sfL https://get.k3s.io | sh -
```

## Set the kubeconfig if required
```
export KUBECONFIG=/etc/rancher/k3s/k3s.yaml
```

## check if the node is running
```
sudo kubectl get nodes
```

## Copy the YAMl files for auto deploy
```
cp *yaml /var/lib/rancher/k3s/server/manifests/ 
```

## check if the application is running

```
kubectl get ingress
```
