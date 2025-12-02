# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/brettmbates/argocd-example-apps
# cd into the cloned directory
git checkout 48ab530c88c9e77c682d703712c2bfddfd2b9263
helm template . --name-template development-helm-guestbook --include-crds
```
