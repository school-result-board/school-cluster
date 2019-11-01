# School Cluster

A helm chart to deploy the school cluster. Has two deployment files for pods and services. 
In order for services to work correctly we need to enable dns on kubernetes. This can be enable on 
microk8s using the command.
 
``` console
$ microk8s.enable dns
``` 

## Pods
* student-app
* score-app
* discovery-app
* result-app

## Services 
* student-service
* score-service
* discovery-service
* result-service
