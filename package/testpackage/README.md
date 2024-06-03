# testpackage

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testpackage`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testpackage`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testpackage
kpt live apply testpackage --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
