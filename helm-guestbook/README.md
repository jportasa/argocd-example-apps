
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout d63e43ac744b0133a37df21ad2e3d37f2237486b
helm template . --name-template prod-helm-guestbook --include-crds
```