evman
=====

.env file manager

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/evman.svg)](https://npmjs.org/package/evman)
[![Downloads/week](https://img.shields.io/npm/dw/evman.svg)](https://npmjs.org/package/evman)
[![License](https://img.shields.io/npm/l/evman.svg)](https://github.com/[object Object]/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g evman
$ envman COMMAND
running command...
$ envman (-v|--version|version)
evman/0.0.0 linux-x64 node-v14.18.1
$ envman --help [COMMAND]
USAGE
  $ envman COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`envman hello [FILE]`](#envman-hello-file)
* [`envman help [COMMAND]`](#envman-help-command)

## `envman hello [FILE]`

describe the command here

```
USAGE
  $ envman hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ envman hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/gustavofsantos/envman/blob/v0.0.0/src/commands/hello.ts)_

## `envman help [COMMAND]`

display help for envman

```
USAGE
  $ envman help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_
<!-- commandsstop -->
