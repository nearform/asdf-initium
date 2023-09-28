<div align="center">

# asdf-initium [![Build](https://github.com/nearform/asdf-initium/actions/workflows/build.yml/badge.svg)](https://github.com/nearform/asdf-initium/actions/workflows/build.yml) [![Lint](https://github.com/nearform/asdf-initium/actions/workflows/lint.yml/badge.svg)](https://github.com/nearform/asdf-initium/actions/workflows/lint.yml)

[initium](https://initium.nearform.com) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add initium
# or
asdf plugin add initium https://github.com/nearform/asdf-initium.git
```

initium:

```shell
# Show all installable versions
asdf list-all initium

# Install specific version
asdf install initium latest

# Set a version globally (on your ~/.tool-versions file)
asdf global initium latest

# Now initium commands are available
initium --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nearform/asdf-initium/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [NearForm](https://github.com/nearform/)
