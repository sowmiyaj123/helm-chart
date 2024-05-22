# testHelm

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testHelm`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testHelm`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testHelm
kpt live apply testHelm --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
