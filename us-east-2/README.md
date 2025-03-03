
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 086de802d6c39dc7d7a75fd88b723b14a6afeda4
kustomize build ./user-configuration/production/us-east-2
```