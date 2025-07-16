
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 11fceee26fdb97fdea747f52631b22f7e5e67649
helm template . --name-template prod-helm-guestbook --include-crds
```