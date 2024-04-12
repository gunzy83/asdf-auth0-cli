<div align="center">

# asdf-auth0-cli [![Build](https://github.com/gunzy83/asdf-auth0-cli/actions/workflows/build.yml/badge.svg)](https://github.com/gunzy83/asdf-auth0-cli/actions/workflows/build.yml) [![Lint](https://github.com/gunzy83/asdf-auth0-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/gunzy83/asdf-auth0-cli/actions/workflows/lint.yml)

[auth0-cli](https://github.com/auth0/auth0-cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add auth0-cli
# or
asdf plugin add auth0-cli https://github.com/gunzy83/asdf-auth0-cli.git
```

auth0-cli:

```shell
# Show all installable versions
asdf list-all auth0-cli

# Install specific version
asdf install auth0-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global auth0-cli latest

# Now auth0-cli commands are available
auth0 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gunzy83/asdf-auth0-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ross Williams](https://github.com/gunzy83/)
