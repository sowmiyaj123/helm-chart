# policy-acm-flux

## Description
kpt package for deploying policy-acm helm charts via flux

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] policy-acm-flux`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree policy-acm-flux`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init policy-acm-flux
kpt live apply policy-acm-flux --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
