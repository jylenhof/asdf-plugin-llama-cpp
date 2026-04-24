<div align="center">

# asdf-plugin-llama-cpp [![Build](https://github.com/jylenhof/asdf-plugin-llama-cpp/actions/workflows/build.yml/badge.svg)](https://github.com/jylenhof/asdf-plugin-llama-cpp/actions/workflows/build.yml) [![Lint](https://github.com/jylenhof/asdf-plugin-llama-cpp/actions/workflows/lint.yml/badge.svg)](https://github.com/jylenhof/asdf-plugin-llama-cpp/actions/workflows/lint.yml)

[plugin-llama-cpp](https://github.com/ggml-org/llama.cpp) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add plugin-llama-cpp
# or
asdf plugin add plugin-llama-cpp https://github.com/jylenhof/asdf-plugin-llama-cpp.git
```

plugin-llama-cpp:

```shell
# Show all installable versions
asdf list-all plugin-llama-cpp

# Install specific version
asdf install plugin-llama-cpp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global plugin-llama-cpp latest

# Now plugin-llama-cpp commands are available
llama-cli --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jylenhof/asdf-plugin-llama-cpp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Yves LENHOF](https://github.com/jylenhof/)
