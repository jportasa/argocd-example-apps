
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 964cad24f8142bf9f379b1f3e9a48f06ceded62f
helm template . --name-template prod-helm-guestbook --include-crds
```