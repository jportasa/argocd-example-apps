
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 3371114567c37e397cd2ae170341a7ddbc4c0e31
helm template . --name-template prod-helm-guestbook --include-crds
```