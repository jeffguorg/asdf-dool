<div align="center">

# asdf-dool [![Build](https://github.com/jeffguorg/asdf-dool/actions/workflows/build.yml/badge.svg)](https://github.com/jeffguorg/asdf-dool/actions/workflows/build.yml) [![Lint](https://github.com/jeffguorg/asdf-dool/actions/workflows/lint.yml/badge.svg)](https://github.com/jeffguorg/asdf-dool/actions/workflows/lint.yml)

[dool](https://github.com/jeffguorg/asdf-dool) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `python`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add dool
# or
asdf plugin add dool https://github.com/jeffguorg/asdf-dool.git
```

dool:

```shell
# Show all installable versions
asdf list-all dool

# Install specific version
asdf install dool latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dool latest

# Now dool commands are available
dool --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jeffguorg/asdf-dool/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [guochao](https://github.com/jeffguorg/)
