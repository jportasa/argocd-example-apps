
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 5acd743a3e01f5721b62ff94f6c0457f9f4fa1b6
helm template . --name-template development-helm-guestbook --include-crds
```