
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout cf6323d0c7b9ed254766aabb43bc20e524e6c503
kustomize build ./user-configuration/development
```