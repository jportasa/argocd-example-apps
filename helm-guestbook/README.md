
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 7b0f2eb3fde0ed7977024320f3328c48dce9f2e0
helm template . --name-template staging-helm-guestbook --include-crds
```