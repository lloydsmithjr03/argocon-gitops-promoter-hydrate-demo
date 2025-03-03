
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout f8827f2f0d7c37e07e18557ae4e78633e93e33ee
kustomize build ./user-configuration/production/us-west-1
```