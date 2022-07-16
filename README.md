# Kubernetes-Tutorial [Link Udemy](https://www.udemy.com/course/learn-kubernetes/)
 Kubernetes for the Absolute Beginners - Hands-on
## Kubernetes Overview
```cmd
It is a container orchestration technology used to orchestrate the deployment and management of hundreds
and thousands of containers in a clustered environment.
```
<img src="./image/components.png" alt="attribute of kubernetes" >

### API server
* The API server acts as the front-end for kubernetes. The users, management devices,
Command line interfaces all talk to the API server to interact with the kubernetes
cluster.
### ETCD
* ETCD is a distributed reliable key-value store used by kubernetes to store all data used to manage the cluster.
* Think of it this way, when you have multiple nodes and multiple masters in your cluster, etcd stores all that information on all the nodes in the cluster in a distributed manner.
* ETCD is responsible for implementing locks within the cluster to ensure there are no conflicts between the Masters.
