<div align="center">

# asdf-promtool [![Build](https://github.com/asdf-community/asdf-promtool/actions/workflows/build.yml/badge.svg)](https://github.com/asdf-community/asdf-promtool/actions/workflows/build.yml) [![Lint](https://github.com/asdf-community/asdf-promtool/actions/workflows/lint.yml/badge.svg)](https://github.com/asdf-community/asdf-promtool/actions/workflows/lint.yml)

[promtool](https://prometheus.io/docs/prometheus/latest/command-line/promtool/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add promtool
# or
asdf plugin add promtool https://github.com/promtool/asdf-promtool.git
```

promtool:

```shell
# Show all installable versions
asdf list-all promtool

# Install specific version
asdf install promtool latest

# Set a version globally (on your ~/.tool-versions file)
asdf global promtool latest

# Now promtool commands are available
promtool --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/asdf-community/asdf-promtool/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [czchen](https://github.com/czchen/)
