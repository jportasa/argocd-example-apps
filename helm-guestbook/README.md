
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout a72c5983e15dd1a316b9a5060d30261a2fd82f36
helm template . --name-template development-helm-guestbook --include-crds
```