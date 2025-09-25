<div align="center">

# asdf-termframe [![Build](https://github.com/jrmolin/asdf-termframe/actions/workflows/build.yml/badge.svg)](https://github.com/jrmolin/asdf-termframe/actions/workflows/build.yml) [![Lint](https://github.com/jrmolin/asdf-termframe/actions/workflows/lint.yml/badge.svg)](https://github.com/jrmolin/asdf-termframe/actions/workflows/lint.yml)

[termframe](https://github.com/pamburus/termframe) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add termframe
# or
asdf plugin add termframe https://github.com/jrmolin/asdf-termframe.git
```

termframe:

```shell
# Show all installable versions
asdf list-all termframe

# Install specific version
asdf install termframe latest

# Set a version globally (on your ~/.tool-versions file)
asdf global termframe latest

# Now termframe commands are available
termframe --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jrmolin/asdf-termframe/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jonathan Molinatto](https://github.com/jrmolin/)
