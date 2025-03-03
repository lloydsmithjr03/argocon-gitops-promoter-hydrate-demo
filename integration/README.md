
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout d1fb39df356a36ed53d4e052a7b473588e6ef4ca
kustomize build ./user-configuration/staging/integration
```