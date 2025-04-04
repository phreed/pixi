<!--- This file is autogenerated. Do not edit manually! -->
# <code>[pixi](../../pixi.md) [global](../global.md) uninstall</code>

## About
Uninstalls environments from the global environment.

--8<-- "docs/reference/cli/pixi/global/uninstall_extender:description"

## Usage
```
pixi global uninstall [OPTIONS] <ENVIRONMENT>...
```

## Arguments
- <a id="arg-<ENVIRONMENT>" href="#arg-<ENVIRONMENT>">`<ENVIRONMENT>`</a>
:  Specifies the environments that are to be removed
<br>May be provided more than once.
<br>**required**: `true`

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

## Description
Uninstalls environments from the global environment.

Example: `pixi global uninstall pixi-pack rattler-build`


--8<-- "docs/reference/cli/pixi/global/uninstall_extender:example"
