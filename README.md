# Setup AliCloud Workspace

A composite action refer the [docs](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action)
including these actions:

1. [Docker Login](https://github.com/marketplace/actions/docker-login)
2. [Setting context for Kubernetes cluster of Alibaba Cloud Kubernetes Service (ACK)](https://github.com/marketplace/actions/setting-context-for-kubernetes-cluster-of-alibaba-cloud-kubernetes-service-ack)

## Inputs

| Action inputs         | Description                             |
|-----------------------|-----------------------------------------|
| acr-registry          | AliCloud ACR registry endpoint          |
| acr-username          | AliCloud ACR registry username          |
| acr-password          | AliCloud ACR registry password          |
| ack-cluster-id        | AliCloud ACK cluster id                 |
| ack-access-key-id     | AliCloud accessKey to access ACK        |
| ack-access-key-secret | AliCloud accessKey secret to access ACK |

## Outputs

None

## Troubleshooting

TBD
