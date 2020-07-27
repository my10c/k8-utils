# k8-utils

Various Kubernetes scripts

## Kubernetes Registry
Script to run your own Docker images registry

NOTES:

 - need to add the secret with:
```
 docker secret create my.crt certs/my.crt
 docker secret create my.key certs/my.key
 ```
  - adjust the variables to your needs, see the script variables section


### docker_registry
Script to build, destroy a Docker registry and start or stop the registry container and get registry container status

### service_registry
Script to create, destroy a registry service and get status is service exist
*WORK IN PROGRESS*


enjoy

- momo
