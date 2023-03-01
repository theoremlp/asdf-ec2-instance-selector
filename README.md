<div align="center">

# asdf-ec2-instance-selector [![Build](https://github.com/theoremlp/asdf-ec2-instance-selector/actions/workflows/build.yml/badge.svg)](https://github.com/theoremlp/asdf-ec2-instance-selector/actions/workflows/build.yml) [![Lint](https://github.com/theoremlp/asdf-ec2-instance-selector/actions/workflows/lint.yml/badge.svg)](https://github.com/theoremlp/asdf-ec2-instance-selector/actions/workflows/lint.yml)


[ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ec2-instance-selector
# or
asdf plugin add ec2-instance-selector https://github.com/theoremlp/asdf-ec2-instance-selector.git
```

ec2-instance-selector:

```shell
# Show all installable versions
asdf list-all ec2-instance-selector

# Install specific version
asdf install ec2-instance-selector latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ec2-instance-selector latest

# Now ec2-instance-selector commands are available
ec2-instance-selector --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/theoremlp/asdf-ec2-instance-selector/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mark Elliot](https://github.com/theoremlp/)
