## Kubernetes Commands

### kubectl
Kubectl is a Command line tool for communicating with a Kubernetes cluster.

##### Kubernetes version running on nodes

```bash
kubectl version
```
##### Number of nodes

```bash
kubectl get nodes
```
##### Command to create a pod and deploy docker container in PODs

```bash
kubectl run mysql --image mysql
```
##### List of PODS in Cluster

```bash
kubectl get pods
```
##### Get information about POD

```bash
kubectl describe pod mysql
```
##### Additional Information about POD

```bash
kubectl get pods -o wide
```
##### Create POD using pod-definition.yml file

```bash
kubectl create -f pod-definition.yml
```
