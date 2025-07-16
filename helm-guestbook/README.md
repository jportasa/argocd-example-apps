
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout eae5163ace4cb99615482f7949baa3077a207958
helm template . --name-template prod-helm-guestbook --include-crds
```