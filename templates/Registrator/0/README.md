# Registrator

## Info

This templates creates a global service that deploys a Consul agent that is bound to the host's networking. This allows all Rancher hosts to join an existing Consul cluster.

Additionally, Registrator is deployed to automatically discover and register containers that are deployed on the host as Consul service entries. This allows for automatic service registration in Consul as Rancher schedule containers in the cluster.

The variables used in this template include:

* Hostname or IP address for the Consul cluster to join (optional :port)

The templates uses the official Registrator images

* registrator.

## Usage

1. Enter the hostname/DNS name/IP address of the Consul server to join

2. Enter in certs.

3. Click deploy.