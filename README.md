> **Warning**
>
> This repository is not maintained anymore, get `zbctl` from asdf using https://github.com/camunda-community-hub/asdf-zbctl instead.

---



<div align="center">

# asdf-zbctl [![Build](https://github.com/multani/asdf-zbctl/actions/workflows/build.yml/badge.svg)](https://github.com/multani/asdf-zbctl/actions/workflows/build.yml) [![Lint](https://github.com/multani/asdf-zbctl/actions/workflows/lint.yml/badge.svg)](https://github.com/multani/asdf-zbctl/actions/workflows/lint.yml)


[zbctl](https://docs.camunda.io/docs/apis-clients/cli-client/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add zbctl
# or
asdf plugin add zbctl https://github.com/multani/asdf-zbctl.git
```

zbctl:

```shell
# Show all installable versions
asdf list-all zbctl

# Install specific version
asdf install zbctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zbctl latest

# Now zbctl commands are available
zbctl version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/multani/asdf-zbctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jonathan Ballet](https://github.com/multani/)
