# gogowiki

## Web-app
Simple Golang based app that allows you to create/view/edit wiki-like pages
for local build:
'''$ go build -o bin/gogowiki main.go'''

for local docker build:
'''$ docker build -t gogowiki:local .'''

## TODO

- [ ] Make app work with mongo DB
- [ ] Update automation for local docker run of mongodb with app
- [ ] Prepare terraform for cloud infrastructure deployment:
  - [ ] Kubernetes cluster
  - [ ] Domain infrastructure
  - [ ] Roles
  - [ ] Load Balancing
  - [ ]  