
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 98d36db85ab9911cdb9cd2bb229eb30b98f550c7
kustomize build ./user-configuration/development
```