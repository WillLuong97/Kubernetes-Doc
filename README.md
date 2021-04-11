# Kubernetes-Doc

## What is Kubernetes: 
- Kubernetes is also known as K8S (The k at the beginning of the word, the 8 words between K and S and then the S)
- Kubernetes is the Application Orchestrator:
    + Deploy and manage applications (containers)
    + Scale up and down according to demand as each code environment are seperate
    + Zero downtime deployments
    + Rollbacks

## Cluster: 
- To understand what is Kubernetes, we have to understand what a Cluster is
- A cluster is a set of nodes, where a node can be a Virtual Machine (VM) or Physical Machine (AWS, Azure, Google Cloud or on-prem)

### Kubernetes Cluster: 
![Kubernetes-Cluster](/media/Kub-Cluster.png)

- Master node: is simply the brain of the cluster, where all of the logic and decision are made. 

- Worker node: All the heavy lifting happens, such as running your application.

- Both master and worker node communicate with each other via the kubectl.

- Within a cluster, there are often more than one worker node. 

![Kubernetes-Cluster-Multiple](/media/Kub-Cluster-2.png)

- As the cluster expands, there are more worker cluster to handle by the master node, which forms the concept of a Control Plane

![Control-Plane](/media/Control-Plane.png)


## minikube
- When we need to run a local cluster, it is important that we use the Minikube

- You should use Minikube because: 
    + Great community
    + Add-ons and lots of features. 
    + Great documentation

- Installation: Docker + Minikube

## Kubectl

+ Kubernetes Command Line Tool
+ Run commands against your cluster
    + Deploy
    + Inspect
    + Edit resources
    + Debug
    + View logs 


