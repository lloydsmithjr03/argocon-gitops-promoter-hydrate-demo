
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout b55b91f7e09652a6013330c13063f2c6a11f28c5
kustomize build ./user-configuration/production/us-west-1
```