# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test zbctl https://github.com/multani/asdf-zbctl.git "zbctl version"
```

Tests are automatically run in GitHub Actions on push and PR.
