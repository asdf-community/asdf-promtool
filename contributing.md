# Contributing

Testing Locally:

```shell
asdf plugin test promtool https://github.com/asdf-community/asdf-promtool [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] "promtool --version"

asdf plugin test promtool https://github.com/asdf-community/asdf-promtool.git "promtool --version"
```

Tests are automatically run in GitHub Actions on push and PR.
