# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test age https://github.com/attakei/asdf-age.git "age --help"
```

Tests are automatically run in GitHub Actions on push and PR.
