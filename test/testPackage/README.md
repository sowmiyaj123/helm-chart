# testPackage

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testPackage`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testPackage`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testPackage
kpt live apply testPackage --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
