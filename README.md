# helm-homelab

A collection of Helm charts used in my homelab. These charts are for applications that do not have an official Helm chart or for my own software.

## Usage

Add this repository to Helm and install charts as needed:

```sh
helm repo add homelab https://dakoel.github.io/helm-homelab
helm install my-release homelab/<chart>
```

For more detailed examples, see my [argocd-homelab](https://github.com/dakoel/argocd-homelab) repository.
