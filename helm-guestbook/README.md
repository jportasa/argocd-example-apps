
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout dabe8e1c2251d283635001e3434dd7ecb93f5e3e
helm template . --name-template prod-helm-guestbook --include-crds
```