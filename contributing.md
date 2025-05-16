# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test maru https://github.com/rothandrew/asdf-maru.git "maru version"
```

Tests are automatically run in GitHub Actions on push and PR.
