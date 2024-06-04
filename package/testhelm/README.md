# testhelm

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testhelm`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testhelm`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testhelm
kpt live apply testhelm --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
