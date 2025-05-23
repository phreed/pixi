<!--- This file is autogenerated. Do not edit manually! -->
# <code>[pixi](../../../pixi.md) [global](../../global.md) [shortcut](../shortcut.md) remove</code>

## About
Remove shortcuts from your machine

--8<-- "docs/reference/cli/pixi/global/shortcut/remove_extender:description"

## Usage
```
pixi global shortcut remove [OPTIONS] [SHORTCUT]...
```

## Arguments
- <a id="arg-<SHORTCUT>" href="#arg-<SHORTCUT>">`<SHORTCUT>`</a>
:  The shortcut that should be removed
<br>May be provided more than once.

## Config Options
- <a id="arg---tls-no-verify" href="#arg---tls-no-verify">`--tls-no-verify`</a>
:  Do not verify the TLS certificate of the server
- <a id="arg---auth-file" href="#arg---auth-file">`--auth-file <AUTH_FILE>`</a>
:  Path to the file containing the authentication token
- <a id="arg---pypi-keyring-provider" href="#arg---pypi-keyring-provider">`--pypi-keyring-provider <PYPI_KEYRING_PROVIDER>`</a>
:  Specifies whether to use the keyring to look up credentials for PyPI
<br>**options**: `disabled`, `subprocess`
- <a id="arg---concurrent-solves" href="#arg---concurrent-solves">`--concurrent-solves <CONCURRENT_SOLVES>`</a>
:  Max concurrent solves, default is the number of CPUs
- <a id="arg---concurrent-downloads" href="#arg---concurrent-downloads">`--concurrent-downloads <CONCURRENT_DOWNLOADS>`</a>
:  Max concurrent network requests, default is `50`

--8<-- "docs/reference/cli/pixi/global/shortcut/remove_extender:example"
