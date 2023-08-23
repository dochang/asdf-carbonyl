<!-- markdownlint-disable MD041 -->
<div align="center">

# asdf-carbonyl

[![Build](https://github.com/dochang/asdf-carbonyl/actions/workflows/build.yml/badge.svg)](https://github.com/dochang/asdf-carbonyl/actions/workflows/build.yml)
[![Lint](https://github.com/dochang/asdf-carbonyl/actions/workflows/lint.yml/badge.svg)](https://github.com/dochang/asdf-carbonyl/actions/workflows/lint.yml)
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/dochang/asdf-carbonyl/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/dochang/asdf-carbonyl/tree/main)


[carbonyl](https://fathy.fr/carbonyl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.
- `ASDF_CARBONYL`: set this environment variable in your shell config to load the correct version of Carbonyl.

# Install

Plugin:

```shell
asdf plugin add carbonyl
# or
asdf plugin add carbonyl https://github.com/dochang/asdf-carbonyl.git
```

carbonyl:

```shell
# Show all installable versions
asdf list-all carbonyl

# Install specific version
asdf install carbonyl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global carbonyl latest

# Now carbonyl commands are available
carbonyl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dochang/asdf-carbonyl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Wade Zhang](https://github.com/dochang/)
