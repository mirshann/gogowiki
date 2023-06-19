# gogowiki

## Web-app
Simple Golang based app that allows you to create/view/edit wiki-like pages
for local build:
'''$ go build -o bin/gogowiki main.go'''

for local docker build:
'''$ docker build -t gogowiki:local .'''

## TODO

### Iteration 0: Manual deployment

![Architecture](img/gogowiki.svg)

1. Container Host
2. CI host (Jenkins)
3. Secret storage host/service (Vault)

### Iteration 1: automated deployment

1. Terraform for infrastructure in Iteration 0
2. Kubernetes cluster automated deployment
3. 