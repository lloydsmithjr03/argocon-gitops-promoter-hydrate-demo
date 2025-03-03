
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/lloydsmithjr03/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 2ed27b3a4fcbb363ec3dd71996cb9397cc5e9658
kustomize build ./user-configuration/staging/integration
```