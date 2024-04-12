# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test auth0-cli https://github.com/gunzy83/asdf-auth0-cli.git "auth0 --version"
```

Tests are automatically run in GitHub Actions on push and PR.
