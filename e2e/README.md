
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 329f8e55afc8de6bec03fd952432405ca175c898
kustomize build ./user-configuration/staging/e2e
```