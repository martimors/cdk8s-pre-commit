# cdk8s pre-commit hook

Created with [pre-commit-mirror-maker](https://github.com/pre-commit/pre-commit-mirror-maker).

To generate a new hook or update this one,

```sh
pre-commit-mirror cdk8s-pre-commit --language node --package-name cdk8s-cli --description "Pre-commit hook for cdk8s" --files-regex ".*cdk8s\.ya?ml$" --entry cdk8s
```
