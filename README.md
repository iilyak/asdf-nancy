<div align="center">

# asdf-nancy [![Build](https://github.com/iilyak/asdf-nancy/actions/workflows/build.yml/badge.svg)](https://github.com/iilyak/asdf-nancy/actions/workflows/build.yml) [![Lint](https://github.com/iilyak/asdf-nancy/actions/workflows/lint.yml/badge.svg)](https://github.com/iilyak/asdf-nancy/actions/workflows/lint.yml)


[nancy](https://github.com/sonatype-nexus-community/nancy) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add nancy
# or
asdf plugin add nancy https://github.com/iilyak/asdf-nancy.git
```

nancy:

```shell
# Show all installable versions
asdf list-all nancy

# Install specific version
asdf install nancy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global nancy latest

# Now nancy commands are available
nancy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iilyak/asdf-nancy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ILYA Khlopotov](https://github.com/iilyak/)
