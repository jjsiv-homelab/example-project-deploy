# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:jjsiv-homelab/example-project-deploy.git
# cd into the cloned directory
git checkout ef23c9dbae35a6b88bb73d4a69d2271b084826b2
kustomize build ./example-go-app/overlays/dev --enable-helm
```
