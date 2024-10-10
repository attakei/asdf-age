<div align="center">

# asdf-age [![Build](https://github.com/attakei/asdf-age/actions/workflows/build.yml/badge.svg)](https://github.com/attakei/asdf-age/actions/workflows/build.yml) [![Lint](https://github.com/attakei/asdf-age/actions/workflows/lint.yml/badge.svg)](https://github.com/attakei/asdf-age/actions/workflows/lint.yml)

[age](https://age.attakei.dev) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add age
# or
asdf plugin add age https://github.com/attakei/asdf-age.git
```

age:

```shell
# Show all installable versions
asdf list-all age

# Install specific version
asdf install age latest

# Set a version globally (on your ~/.tool-versions file)
asdf global age latest

# Now age commands are available
age --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/attakei/asdf-age/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kazuya Takei](https://github.com/attakei/)
