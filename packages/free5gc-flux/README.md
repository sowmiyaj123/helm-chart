# free5gc-flux

## Description
kpt package for deploying free5gc helm charts via flux

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] free5gc-flux`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree free5gc-flux`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init free5gc-flux
kpt live apply free5gc-flux --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
