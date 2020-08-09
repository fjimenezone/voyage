# Environment Variables
## Helm and configmap
Using Helm to template a configmap. A deployment uses the configmap

### The approach
* A conf directory is created outside the template directory.
* The configmap is modified to read from any yaml in conf directory
