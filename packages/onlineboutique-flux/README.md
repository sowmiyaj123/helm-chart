# onlineboutique-flux

## Description
kpt package for deploying online boutique helm via flux

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] onlineboutique-flux`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree onlineboutique-flux`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init onlineboutique-flux
kpt live apply onlineboutique-flux --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
