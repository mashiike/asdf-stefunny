<div align="center">

# asdf-stefunny [![Build](https://github.com/mashiike/asdf-stefunny/actions/workflows/build.yml/badge.svg)](https://github.com/mashiike/asdf-stefunny/actions/workflows/build.yml) [![Lint](https://github.com/mashiike/asdf-stefunny/actions/workflows/lint.yml/badge.svg)](https://github.com/mashiike/asdf-stefunny/actions/workflows/lint.yml)

[stefunny](https://github.com/mashiike/stefunny) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add stefunny
# or
asdf plugin add stefunny https://github.com/mashiike/asdf-stefunny.git
```

stefunny:

```shell
# Show all installable versions
asdf list-all stefunny

# Install specific version
asdf install stefunny latest

# Set a version globally (on your ~/.tool-versions file)
asdf global stefunny latest

# Now stefunny commands are available
stefunny --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mashiike/asdf-stefunny/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ikeda MASASHI](https://github.com/mashiike/)
