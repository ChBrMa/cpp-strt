cpp-strt
========

C++ project generator

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/cpp-strt.svg)](https://npmjs.org/package/cpp-strt)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/ChBrMa/cpp-strt?branch=master&svg=true)](https://ci.appveyor.com/project/ChBrMa/cpp-strt/branch/master)
[![Downloads/week](https://img.shields.io/npm/dw/cpp-strt.svg)](https://npmjs.org/package/cpp-strt)
[![License](https://img.shields.io/npm/l/cpp-strt.svg)](https://github.com/ChBrMa/cpp-strt/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g cpp-strt
$ cppst COMMAND
running command...
$ cppst (-v|--version|version)
cpp-strt/0.0.0 win32-x64 node-v14.18.0
$ cppst --help [COMMAND]
USAGE
  $ cppst COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`cppst hello [FILE]`](#cppst-hello-file)
* [`cppst help [COMMAND]`](#cppst-help-command)

## `cppst hello [FILE]`

describe the command here

```
USAGE
  $ cppst hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ cppst hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/ChBrMa/cpp-strt/blob/v0.0.0/src/commands/hello.ts)_

## `cppst help [COMMAND]`

display help for cppst

```
USAGE
  $ cppst help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.4/src/commands/help.ts)_
<!-- commandsstop -->
