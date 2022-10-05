# Introduction

## Kubernetes
Kubernetes is an open-source container management also known as container orchestration tool for automating software deployment, scaling, and management.

## Container Orchestration
Orchestration enables developers to easily build containerized applications and services, as well as scale, schedule and monitor those containers.

## Nodes
Nodes are physical or virtual machine in which kubernetes is installed.

## Cluster
Cluster is group of nodes, if one node fails we have our application accessible from other nodes.

## Master
Master is other node in which kubernetes is installed and it manages other nodes

## Components
- API Server
- etcd
- kubelet
- Container Runtime
- Controller
- Scheduler

## Master V/S Worker node
Master has kube-apiserver installed and nodes have kubelet installed (Kubelet is an agent which make sure nodes are healthy) which provides information to master which stores information in etcd (key value storage)

## Minikube
Minikube is a lightweight Kubernetes implementation that creates a VM on your local machine and deploys a simple cluster containing only one node. 
- Download kubectl and minikube to start using minikube

## PODS
A Pod is a group of one or more containers, with shared storage and network resources, and a specification for how to run the containers.

## Replication Controllers

Replication Controller used for high availability, it ensures that a specified number of pod replicas are running at any one time. It also helps load balancing and scaling when demand increases.

## ReplicaSets
ReplicaSets replaced replication controllers. A ReplicaSet's purpose is to maintain a stable set of replica Pods running at any given time.



