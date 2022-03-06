# github-actions

My collection of reusable Github Action workflows.

## Workflows

### go-ci.yaml

Performs standard build, and test for go programs.

Inputs:

* `go-version`: a string with the go version to use, defaults to 1.17

## Dependencies

* https://github.com/actions/checkout: to checkout code
* https://github.com/actions/setup-go: to install the go CLI
