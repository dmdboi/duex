Deux
======

A generator for building better Express apps

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/deux.svg)](https://npmjs.org/package/deux)
[![Downloads/week](https://img.shields.io/npm/dw/deux.svg)](https://npmjs.org/package/deux)
[![License](https://img.shields.io/npm/l/deux.svg)](https://github.com/dmdboi/deux/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g express-deux
$ duex COMMAND
running command...
$ duex (-v|--version|version)
express-deux/1.0.0 win32-x64 node-v14.16.0
$ duex --help [COMMAND]
USAGE
  $ duex COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`duex help [COMMAND]`](#duex-help-command)
* [`duex template NAME DIR`](#duex-template-name-dir)

## `duex help [COMMAND]`

display help for duex

```
USAGE
  $ duex help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_

## `duex template NAME DIR`

Clones an existing Express app repository.

```
USAGE
  $ duex template NAME DIR
```

_See code: [src/commands/template.js](https://github.com/dmdboi/duex/blob/v1.0.0/src/commands/template.js)_
<!-- commandsstop -->
