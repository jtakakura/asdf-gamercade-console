# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gamercade-console https://github.com/jtakakura/asdf-gamercade-console.git "gamercade-console --help"
```

Tests are automatically run in GitHub Actions on push and PR.