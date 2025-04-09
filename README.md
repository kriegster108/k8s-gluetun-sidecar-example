# k8s-gluetun-sidecar
A simple K8s deployment example demonstrating sidecar pattern to give containers vpn access via wireguard using gluetun. 


## Setup
Tested on Kubernetes `v1.31.4`
1. Set `WIREGUARD_PRIVATE_KEY` from your provider 
2. Select `VPN_SERVICE_PROVIDER` from pre-existing configurations [here](https://github.com/qdm12/gluetun/tree/master/internal/provider)

Additional configuration options are documented [here](https://github.com/qdm12/gluetun-wiki/tree/main/setup/options)