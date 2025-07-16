
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout da6f08f24bd85f3795a461833cd557c3347573be
helm template . --name-template development-helm-guestbook --include-crds
```