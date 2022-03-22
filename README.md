# deloitte-api-helm

Helm chart for Deloitte API test

## Overview

Helm chart for Deloitte API test. Designed to be deployed in a Kubernetes cluster using ingress controllers.

## Requirements

* Kubernetes cluster installed
* Helm
* Access to the docker image

## Usage

```bash
helm upgrade <RELEASE_NAME> . --install --render-subcharts-notes -n <NAMESPACE_NAME> 
```

## Architectural considerations

* Ingress controller  to be used as traffic ingress point of the application
* Port used in the pod 8080
