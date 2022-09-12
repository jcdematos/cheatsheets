# Kubernetes
## Configuration
| Command | Description |
| - | - |
| `export KUBECONFIG=<config.yml>` | Make kubectl use that config file | 
## Basic
| Command | Description |
| - | - |
| `kubectl get <kind>` | Get information for that kind (pod, dpeloyment, svc, etc) | 
| `kubectl describe <kind> <name>` | Describe the object | 
| `kubectl get pods --namespace=<namespace> -l app=<name> -w | Watch a group of pods |
| `kubectl port-forward <pod/deployment/svc/etc> port:port | Port forward connection to local machine |
