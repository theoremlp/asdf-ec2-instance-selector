# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test ec2-instance-selector https://github.com/theoremlp/asdf-ec2-instance-selector.git "ec2-instance-selector --help"
```

Tests are automatically run in GitHub Actions on push and PR.
