
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout aa8a580f4e87ec37234d4bed1dcfa9e174460e41
helm template . --name-template prod-helm-guestbook --include-crds
```