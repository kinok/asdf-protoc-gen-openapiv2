<div align="center">

# asdf-protoc-gen-openapiv2 [![Build](https://github.com/kinok/asdf-protoc-gen-openapiv2/actions/workflows/build.yml/badge.svg)](https://github.com/kinok/asdf-protoc-gen-openapiv2/actions/workflows/build.yml) [![Lint](https://github.com/kinok/asdf-protoc-gen-openapiv2/actions/workflows/lint.yml/badge.svg)](https://github.com/kinok/asdf-protoc-gen-openapiv2/actions/workflows/lint.yml)

[protoc-gen-openapiv2](https://github.com/kinok/protoc-gen-openapiv2) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add protoc-gen-openapiv2
# or
asdf plugin add protoc-gen-openapiv2 https://github.com/kinok/asdf-protoc-gen-openapiv2.git
```

protoc-gen-openapiv2:

```shell
# Show all installable versions
asdf list-all protoc-gen-openapiv2

# Install specific version
asdf install protoc-gen-openapiv2 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-openapiv2 latest

# Now protoc-gen-openapiv2 commands are available
protoc-gen-openapiv2 --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kinok/asdf-protoc-gen-openapiv2/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [kinok](https://github.com/kinok/)
