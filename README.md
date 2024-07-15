<div align="center">

# asdf-noir [![Build](https://github.com/ptisserand/asdf-noir/actions/workflows/build.yml/badge.svg)](https://github.com/ptisserand/asdf-noir/actions/workflows/build.yml) [![Lint](https://github.com/ptisserand/asdf-noir/actions/workflows/lint.yml/badge.svg)](https://github.com/ptisserand/asdf-noir/actions/workflows/lint.yml)

[noir](https://github.com/noir-lang/noir) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add noir
# or
asdf plugin add noir https://github.com/ptisserand/asdf-noir.git
```

noir:

```shell
# Show all installable versions
asdf list-all noir

# Install specific version
asdf install noir latest

# Set a version globally (on your ~/.tool-versions file)
asdf global noir latest

# Now noir commands are available
noir --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ptisserand/asdf-noir/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Patrice Tisserand](https://github.com/ptisserand/)
