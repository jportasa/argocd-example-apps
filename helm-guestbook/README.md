
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout c2ed7207ec809a4f35bdba6b82eb1cacbdbfa32e
helm template . --name-template prod-helm-guestbook --include-crds
```