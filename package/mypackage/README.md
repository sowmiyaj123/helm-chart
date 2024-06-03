# helmPackage

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] helmPackage`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree helmPackage`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init helmPackage
kpt live apply helmPackage --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
