# flux-helm

## Description

kpt package for provisioning flux helm-controller and source-controller

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] flux-helm`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree flux-helm`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init flux-helm
kpt live apply flux-helm --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/