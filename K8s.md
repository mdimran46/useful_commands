## Kubernetes basic commands
- kubectl run PODNAME --image=image-name
- kubectl get pods
- kubectl describe PODNAME
- kubectl get pods -o wide [provide the details with used Node]
- kubectl delete pod PODNAME

- kubectl run redis --image=redis123 --dry-run=client -o yaml > redis-definition.yaml
kubectl create -f redis-definition.yaml
    > Update the pod-definition file and use kubectl apply command or use kubectl edit pod redis command.