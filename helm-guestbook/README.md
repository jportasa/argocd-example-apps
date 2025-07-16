
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 87ce170a62ea0426d480214289c34bd2c1a20089
helm template . --name-template prod-helm-guestbook --include-crds
```