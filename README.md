
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 06d0d8004d01f275c4cbe0642aa4d502c4a01955
kustomize build ./user-configuration/development
```