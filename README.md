
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 2356cfe6e24adfca55bd9af53b026db7cfa0aca9
kustomize build ./user-configuration/development
```