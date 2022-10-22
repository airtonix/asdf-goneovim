# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test goneovim https://github.com/airtonix/asdf-goneovim.git "goneovim --help"
```

Tests are automatically run in GitHub Actions on push and PR.
