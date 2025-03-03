
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 82dfa67d8ed43d8d44c9b1c7cbe7b35d1e335f50
kustomize build ./user-configuration/development
```