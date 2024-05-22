# ueransim-flux

## Description
kpt package for deploying free5gc ueransim helm via flux

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] ueransim-flux`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree ueransim-flux`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init ueransim-flux
kpt live apply ueransim-flux --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
