
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout d1409e394a4561247148b3a2a09b86f36f133961
kustomize build ./user-configuration/staging/integration
```