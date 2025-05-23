<!--- This file is autogenerated. Do not edit manually! -->
# <code>[pixi](../../pixi.md) [workspace](../workspace.md) environment</code>

## About
Commands to manage project environments

--8<-- "docs/reference/cli/pixi/workspace/environment_extender:description"

## Usage
```
pixi workspace environment [OPTIONS] <COMMAND>
```

## Subcommands
| Command | Description |
|---------|-------------|
| [`add`](environment/add.md) | Adds an environment to the manifest file |
| [`list`](environment/list.md) | List the environments in the manifest file |
| [`remove`](environment/remove.md) | Remove an environment from the manifest file |


## Global Options
- <a id="arg---manifest-path" href="#arg---manifest-path">`--manifest-path <MANIFEST_PATH>`</a>
:  The path to `pixi.toml`, `pyproject.toml`, or the workspace directory

--8<-- "docs/reference/cli/pixi/workspace/environment_extender:example"
