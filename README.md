buttercms
=========

CLI tool to work with ButterCMS

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/buttercms.svg)](https://npmjs.org/package/buttercms-cli)
[![Downloads/week](https://img.shields.io/npm/dw/buttercms.svg)](https://npmjs.org/package/buttercms-cli)
[![License](https://img.shields.io/npm/l/buttercms.svg)](https://github.com/deleteman/buttercms-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g buttercms-cli
$ buttercms COMMAND
running command...
$ buttercms (-v|--version|version)
buttercms-cli/0.0.3 darwin-x64 node-v9.8.0
$ buttercms --help [COMMAND]
USAGE
  $ buttercms COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`buttercms generate:blog`](#buttercms-generateblog)
* [`buttercms help [COMMAND]`](#buttercms-help-command)

## `buttercms generate:blog`

```
USAGE
  $ buttercms generate:blog

OPTIONS
  --for=express  Target destination for the generator command
```

_See code: [src/commands/generate/blog.js](https://github.com/buttercms/buttercms-cli/blob/v0.0.3/src/commands/generate/blog.js)_

## `buttercms help [COMMAND]`

display help for buttercms

```
USAGE
  $ buttercms help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.2/src/commands/help.ts)_
<!-- commandsstop -->
