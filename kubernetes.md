# Kubernetes
## Configuration
| Command | Description |
| - | - |
| `export KUBECONFIG=<config.yml>` | Make kubectl use that config file | 

## Kubernetes Objects
| Object | Usage on kubectl |
| - | - |
| Pod | pod | 
| Job | job |
| CronJob | cronjob |
| Deployment | deploy, deployment |
| Service | service,svc |
| Events | events |
| ConfigMap | configmap |
| Secrets | secret | 
| PersistentVolume | persistentvolume,pv |

## General
| Command                                                     | Description                                                              |
| -                                                           | -                                                                        |
| `kubectl get <kind>`                                        | Get information for that kind (pod, dpeloyment, svc, etc)                |
| `kubectl get <kind> -o json`                                | Get information for that kind in detailed json format                    |
| `kubectl get pods --namespace=<namespace> -l app=<name> -w` | Watch a group of pods                                                    |
| `kubectl describe <kind> <name>`                            | Describe the object                                                      |
| `kubectl create deployment <name> --image=image`            | Create a deployment based on the container image ginve                   |
| `kubectl create -f <yaml-files/folder`                      | Crete objects based on file templates                                    |
| `kubectl edit <kind> <name>`                                | Edit the object using default text editor and apply changes after saving |
| `kubectl apply -f <yaml-files/folder>`                      | Create or update objects based on file templates                         |
| `kubectl port-forward <pod/deployment/svc/etc> port:port`   | Port forward connection to local machine                                 |

## Pods
| Command | Description |
| - | - |
| `kubectl get pod --all-namespaces` | List pods on all namespaces|
| `kubectl -n <namespace> get <pod>` | List pods on the given namespace |

## Secrets
| Command | Description |
| - | - |
| `kubectl get secret <secret-name>` | Get information about that secret |
| `kubectl get secret <secret-name> -o jsonpath='{.data.*}' \| base -d` | Get secrets decoded |

## Nodes
| Command | Description |
| - | - |
| `kubectl get nodes` | Get the nodes of your cluster |
| `kubectl drain <node-ip> --force --ignore-daemonsets`| Drain and unschesdule the node |
| `kubectl cordon <node-ip>` | Make a node unschedulable |
| `kubectl uncordon <node-ip>` | Make a node schedulable |


-----
<!-----
Service account is automatically mounted at:
- /var/run/secrets/kubernetes.io/serviceaccount


----->
