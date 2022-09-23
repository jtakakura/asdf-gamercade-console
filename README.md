<div align="center">

# asdf-gamercade-console [![Build](https://github.com/jtakakura/asdf-gamercade-console/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-gamercade-console/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-gamercade-console/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-gamercade-console/actions/workflows/lint.yml)


[gamercade-console](https://gamercade.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add gamercade-console
# or
asdf plugin add gamercade-console https://github.com/jtakakura/asdf-gamercade-console.git
```

gamercade-console:

```shell
# Show all installable versions
asdf list-all gamercade-console

# Install specific version
asdf install gamercade-console latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gamercade-console latest

# Now gamercade_console, gamercade_editor and gccl commands are available
gccl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-gamercade-console/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
