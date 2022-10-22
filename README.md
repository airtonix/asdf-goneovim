<div align="center">

# asdf-goneovim [![Build](https://github.com/airtonix/asdf-goneovim/actions/workflows/build.yml/badge.svg)](https://github.com/airtonix/asdf-goneovim/actions/workflows/build.yml) [![Lint](https://github.com/airtonix/asdf-goneovim/actions/workflows/lint.yml/badge.svg)](https://github.com/airtonix/asdf-goneovim/actions/workflows/lint.yml)


[goneovim](https://github.com/akiyosi/goneovim) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add goneovim
# or
asdf plugin add goneovim https://github.com/airtonix/asdf-goneovim.git
```

goneovim:

```shell
# Show all installable versions
asdf list-all goneovim

# Install specific version
asdf install goneovim latest

# Set a version globally (on your ~/.tool-versions file)
asdf global goneovim latest

# Now goneovim commands are available
goneovim --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/airtonix/asdf-goneovim/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zeno Jiricek](https://github.com/airtonix/)
