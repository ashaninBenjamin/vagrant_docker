# Vagrant-machine to launch docker-а

Unfortunately, mac osx Docker Desktop works slow. But in virtual ubuntu it works better.

Vagrant settings and provision file to install Ubuntu virtual machine to run docker.

## Dependencies
- VirtialBox 6.14+
- Vagrant 2.2.10+
- Ansible 2.9.15+

## Vagrant machine installing soft
- docker 19.03.8
- docker-compose 1.25.4
- Openshift client 1.3.2
- vim, curl, tree, htop
- postgres-client 12

## Build
`vagrant up`

## Use
`vagrant ssh`

## Turn off
`vagrant down`
