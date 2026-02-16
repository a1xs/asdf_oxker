# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test oxker https://github.com/a1xs/asdf-oxker "oxker --help"
```

Tests are automatically run in GitHub Actions on push and PR.
