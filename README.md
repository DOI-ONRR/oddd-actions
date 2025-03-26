# ODDD actions
Reusable workflows and actions

## Usage
```
...
jobs:
  ...
  call-cf-deploy-workflow:
    uses: doi-onrr/oddd-actions/.github/workflows/cf-deploy@v1
    with:
      cf-space: dev
      manifest: manifest.yml
      build-path: ./public
    secrets: inherit
...
```