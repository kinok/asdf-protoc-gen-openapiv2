# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test protoc-gen-openapiv2 https://github.com/kinok/asdf-protoc-gen-openapiv2.git "protoc-gen-openapiv2 --help"
```

Tests are automatically run in GitHub Actions on push and PR.
