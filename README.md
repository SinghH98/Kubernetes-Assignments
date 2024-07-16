# Kubernetes-Assignments Description
Include work for Kubernetes, Mini Kube, Deployment, Nodeport, Ingress, ClusterIP. 

Assignment - 1: 
● Deploy a Kubernetes Cluster for 3 nodes. 
● Create a nginx deployment of 3 replicas.

Assignment - 2:
● Use the previous deployment. 
● Create a service of type NodePort for nginx deployment. 
● Check the nodeport service on a browser to verify. 

Assignment - 3:
● Use the previous deployment. 
● Change the replicas to 5 for the deployment. 

Assignment - 4:
● Use the previous deployment.
● Change the service type to ClusterIP.

Assignment - 5:
● Use the previous deployment. 
● Deploy an nginx deployment of 3 replicas. 
● Create an nginx service of type clusterip. 
● Create an ingress service /apache to apache service /nginx to nginx service. 

CASE STUDY - INTRODUCTION TO KUBERNETES
 
Suppose I have just joined a startup Ventura Software as a Devops Lead Engineer. The company relies on a Monolithic Architecture for its product. Recently, the senior management was hired. The new CTO insists on having a Microservice Architecture. The Development Team, is 
working on breaking the Monolith. Meanwhile, I have been asked to host a Test Application on Kubernetes, to understand how it works.
 
Following things have to be implemented:
 
● Deploy an Apache2 deployment of 2 replicas 
● Sample code has been checked-in at the following Git-Hub repo:
 
https://github.com/hshar/website.git
 . 
I have to containerize this code, and push it to Docker Hub. Once done, deploy it on Kubernetes with 2 replicas.
 
● Deploy Ingress with the following rules: 
i) */apache* should point to the apache pods 
ii) */custom* should point to the GitHub application 
