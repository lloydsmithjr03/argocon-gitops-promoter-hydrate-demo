
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 6c7723eb3b45816e91da5b2852915b4d1b8032cd
kustomize build ./user-configuration/development
```