
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout a8faf03b51ab7bea1d71ccca858c7bcf44cbd3be
helm template . --name-template prod-helm-guestbook --include-crds
```