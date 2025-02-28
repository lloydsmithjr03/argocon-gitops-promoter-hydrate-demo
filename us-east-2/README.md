
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout b8dccfc6695ee1769b7430ad577d1b378f1153f6
kustomize build ./user-configuration/production/us-east-2
```