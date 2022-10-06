# Deployments and Updates

#### Create Deloyment
```
kubectl create -f deployment.yml
```
#### Get Deloyment
```
kubectl get deployments
```
#### Update Deloyment
```
kubectl set image deployment/fitness-app mysql=mysql:8.0
```
#### Status of Deloyment
```
kubectl rollout status deployment/fitness-app
```
```
kubectl rollout history deployment/fitness-app
```
#### Rollback Deloyment
```
kubectl rollout undo deployment/fitness-app
```
