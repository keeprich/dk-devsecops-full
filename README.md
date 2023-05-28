
# DevSecOps - Kubernetes DevOps & Security

These are the code files from the [DevSecOps course](https://kodekloud.com/courses/devsecops/) hosted on KodeKloud.


### Fork and Clone this Repo

### Clone to Desktop and VM

### NodeJS Microservice - Docker Image -

`docker run -p 8787:5000 siddharth67/node-service:v1`

`curl localhost:8787/plusone/99`
 
### NodeJS Microservice - Kubernetes Deployment -
`kubectl create deploy node-app --image siddharth67/node-service:v1`

`kubectl expose deploy node-app --name node-service --port 5000 --type ClusterIP`

`curl node-service-ip:5000/plusone/99`

##Ref:

Talisman – Keep your secrets secret

https://thoughtworks.github.io/talisman/docs

PITest – Mutation Tests

https://pitest.org/quickstart/maven/

Dependency CHeck  Configuration

https://jeremylong.github.io/DependencyCheck/dependency-check-gradle/configuration.html

Trivy Docs

https://aquasecurity.github.io/trivy/v0.18.3/

OPA Conftest – Docker Security

https://github.com/gbrindisi/dockerfile-security

OWASP ZAP – API Scan

https://www.zaproxy.org/docs/docker/api-scan/
