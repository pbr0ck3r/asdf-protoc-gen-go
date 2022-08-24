# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test protoc-gen-go https://github.com/pbr0ck3r/asdf-protoc-gen-go.git "protoc-gen-go --version"
```

Tests are automatically run in GitHub Actions on push and PR.
