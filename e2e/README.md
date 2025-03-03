
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 18a7f981dc4d0bd748ec068017472a8410ef293c
kustomize build ./user-configuration/staging/e2e
```