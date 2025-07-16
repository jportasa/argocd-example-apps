
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 92598393fec5ccbc38318e501875df67451b6fd4
helm template . --name-template prod-helm-guestbook --include-crds
```