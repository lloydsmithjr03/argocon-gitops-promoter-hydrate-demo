
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout a9fa144872eec00b75505a0649ddccc011c69db0
kustomize build ./user-configuration/staging/integration
```