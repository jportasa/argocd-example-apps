
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout a42fc30d12b11e0adae808448900651710e2c92c
helm template . --name-template prod-helm-guestbook --include-crds
```