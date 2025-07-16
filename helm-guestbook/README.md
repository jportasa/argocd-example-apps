
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jportasa/argocd-example-apps
# cd into the cloned directory
git checkout 85e03903eee2bf98f5d6f0c298c8ea240401c89a
helm template . --name-template prod-helm-guestbook --include-crds
```