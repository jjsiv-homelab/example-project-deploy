# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:jjsiv-homelab/example-project-deploy.git
# cd into the cloned directory
git checkout 312aeae19a7530ffb7049cea249770e817751f08
kustomize build ./example-go-app/overlays/staging --enable-helm
```
