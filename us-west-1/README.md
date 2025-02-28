
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout a81c1ec542215f9b7104f69200a9722a7f113448
kustomize build ./user-configuration/production/us-west-1
```