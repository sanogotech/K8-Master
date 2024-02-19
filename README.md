
## Vidéo Master Class

* https://youtu.be/L8n_HYDnq_I?si=a8LkUlnYlIL2D6W9

##:Concepts

- Node / VM/ Virtual Machine
- Node Master vs Node Workers

### Node Master

- Api server
- etcd ( key value db configuration)
- scheduler
- controller ( monitoring)

## Node Workers

- kubproxy
- Kublet
- Pod 1( container 1, n)
- Pod2, ..


## Flow from Api server to pod

- Api server / etcd congig key values
- Scheduler / update etcd
- Kublet
- create pod
- pod state alert Contrôler/ call scheduler

## Install

## Deploy pod

