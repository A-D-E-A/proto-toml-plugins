# Collection of proto plugins

This repository groups TOML plugins for [proto](https://moonrepo.dev/proto).

Plugins included right now:
- [jq](https://jqlang.github.io/jq/)
- [nixpacks](https://nixpacks.com)

## Installation

Here's how to install a plugin (replace *\<toolname\>* with the actual tool's name)

### Global install

```sh
proto plugin add <toolname> "source:https://raw.githubusercontent.com/A-D-E-A/proto-toml-plugins/main/plugins/<toolname>.toml" --global
proto install <toolname>
```

### Per-project install

```sh
proto plugin add <toolname> "source:https://raw.githubusercontent.com/A-D-E-A/proto-toml-plugins/main/plugins/<toolname>.toml"
proto pin <toolname> latest --resolve
```

