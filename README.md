# @qgisk/kv-cli

[![npm version](https://badgen.net/npm/v/@qgisk/kv-cli)](https://npm.im/@qgisk/kv-cli) [![npm downloads](https://badgen.net/npm/dm/@qgisk/kv-cli)](https://npm.im/@qgisk/kv-cli)

## Install

```bash
npm i @qgisk/kv-cli
```

# KV Cli

KV has a simple cli for most commands (everything but all)

## Installation

```bash
npm i -g @qgisk/kv
```

## Help

```bash
kv --help
```

### For specific commands

```bash
kv get -h # or --help
```

## Settings

Default settings

```json
{
    "db": {
        "uri": "mongodb://localhost:27017/kv"
    },
    "namespace": "kv"
}
```

### Updating settings

```bash
kv settings --uri <your uri: string> --namespace <namespace: string>
```

## Setting a value

Supports multi word values

```
kv set [key] [value] --namespace <optional> --ttl [number (in ms)] <optional>
```

## Getting a value

```
kv get [key] --namespace <optional>
```

## Deleting a value

```
kv delete [key] --namespace <optional>
```

## Clearing a namespace

```
kv clear --namespace <optional>
```

## Coming soon / To do

-   Tests for the cli

[MIT](https://github.com/QGIsK/@qgisk/kv-cli/blob/main/LICENSE) Demian
