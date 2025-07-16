
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 3e674a0830b244d0aaeaeef243751343e6c6acf0
helm template . --name-template development-helm-guestbook --include-crds
```