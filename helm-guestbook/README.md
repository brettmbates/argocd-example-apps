# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/brettmbates/argocd-example-apps
# cd into the cloned directory
git checkout 9b580c704a66fad9c96af0268bdf3058cd6d8f91
helm template . --name-template staging-helm-guestbook --include-crds
```
