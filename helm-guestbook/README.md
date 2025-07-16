
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout abe90fe219a3f76a3e6fd485d13a6f85f072c489
helm template . --name-template prod-helm-guestbook --include-crds
```