<div align="center">

# asdf-terrascan [![Build](https://github.com/hpdobrica/asdf-terrascan/actions/workflows/build.yml/badge.svg)](https://github.com/hpdobrica/asdf-terrascan/actions/workflows/build.yml) [![Lint](https://github.com/hpdobrica/asdf-terrascan/actions/workflows/lint.yml/badge.svg)](https://github.com/hpdobrica/asdf-terrascan/actions/workflows/lint.yml)


[terrascan](https://runterrascan.io/docs/getting-started/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add terrascan
# or
asdf plugin add terrascan https://github.com/hpdobrica/asdf-terrascan.git
```

terrascan:

```shell
# Show all installable versions
asdf list-all terrascan

# Install specific version
asdf install terrascan latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terrascan latest

# Now terrascan commands are available
terrascan version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/hpdobrica/asdf-terrascan/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dobrica Savic](https://github.com/hpdobrica/)
