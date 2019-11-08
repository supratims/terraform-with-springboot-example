# A simple Spring Boot application
A simple spring boot application to demostrate how to deploy a simple application on kubernetes using ingress and your own domain name on https ! 
We are using terraform here

## Requirements
* Java 8
* Gradle

### Deployment
* Google cloud platform
* Google kubernetes engine (GKE)

### Terraform
* Replace path in terraform/setup.tf and provide your own gcp credentials
     `  credentials = "${file("/opt/secrets/gcp-secret-59fbc1d0e021.json")}" `
* 
