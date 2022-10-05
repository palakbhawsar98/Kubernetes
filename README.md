## pod-definition.yml

Kubernetes uses yml file as an input to create pods, replicas, deployments, services and so on,

The yml files contain four top level fields-

- apiVersion:  Depending on what we need to create use apiVersion, for creating pods use version v1
- kind: Type of object we want to create such as Pod
- metadata: Data about the object like name, labels and app.
- spec: Specification 
