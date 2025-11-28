# vfox-chezscheme

[vfox](https://github.com/version-fox/vfox) plugin for [Chez Scheme](https://github.com/cisco/ChezScheme).

Chez Scheme is both a programming language and an implementation of that language, with supporting tools and documentation.

**Note:** This plugin compiles Chez Scheme from source. You will need a C compiler (gcc or clang) and make installed on your system.

## Usage with mise

```bash
# Install a specific version (compiles from source)
mise install chezscheme@10.0.0

# Use in current shell
mise use chezscheme@10.0.0

# Run scheme
scheme --version
```

## Usage with vfox

```bash
# Add the plugin
vfox add chezscheme

# Install a version (compiles from source)
vfox install chezscheme@10.0.0

# Use the version
vfox use chezscheme@10.0.0
```

## Requirements

- C compiler (gcc or clang)
- make
- Basic build tools

On Ubuntu/Debian:
```bash
apt-get install build-essential
```

On macOS:
```bash
xcode-select --install
```
