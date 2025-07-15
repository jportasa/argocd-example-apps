
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 4f556ef33fedbcc946c9585ccedcd7653e47bfe5
helm template . --name-template prod-helm-guestbook --include-crds
```