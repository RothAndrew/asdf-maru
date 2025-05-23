<div align="center">

# asdf-maru [![Build](https://github.com/rothandrew/asdf-maru/actions/workflows/build.yml/badge.svg)](https://github.com/rothandrew/asdf-maru/actions/workflows/build.yml) [![Lint](https://github.com/rothandrew/asdf-maru/actions/workflows/lint.yml/badge.svg)](https://github.com/rothandrew/asdf-maru/actions/workflows/lint.yml)

[maru](https://github.com/defenseunicorns/maru-runner) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add maru https://github.com/rothandrew/asdf-maru.git
```

maru:

```shell
# Show all installable versions
asdf list-all maru

# Install specific version
asdf install maru latest

# Set a version globally (on your ~/.tool-versions file)
asdf global maru latest

# Now maru commands are available
maru version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rothandrew/asdf-maru/graphs/contributors)!

# License

See [LICENSE](LICENSE)
