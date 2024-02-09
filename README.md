```sh
export GITHUB_TOKEN=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
export GITHUB_USER=rokonet8
export GITHUB_REPO=flux2-kustomize-helm-example2

flux bootstrap github \
    --context=azure_tf_vm_k3s \
    --owner=${GITHUB_USER} \
    --repository=${GITHUB_REPO} \
    --branch=main \
    --personal \
    --path=clusters/staging
```
