
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 108d929299e343734659d7a0e7ddcdf38f115578
kustomize build ./user-configuration/production/us-east-2
```