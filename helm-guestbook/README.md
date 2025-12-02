# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/brettmbates/argocd-example-apps
# cd into the cloned directory
git checkout 24e3c0f403a4349eb7161b3f286a8816875cbfb7
helm template . --name-template staging-helm-guestbook --include-crds
```
