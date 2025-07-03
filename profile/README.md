# Serial

<a href="https://deno.land"><img align="right" src="https://github.com/Serial-IO/.github/blob/main/assets/profile.svg" height="150px" alt="the serial port standing in the rain"></a>

[![Lint](https://github.com/Serial-IO/serial/actions/workflows/lint.yml/badge.svg)](https://github.com/Serial-IO/serial/actions/workflows/lint.yml)
[![Unit Tests](https://github.com/Serial-IO/serial/actions/workflows/unit_tests.yml/badge.svg)](https://github.com/Serial-IO/serial/actions/workflows/unit_tests.yml)

A [serial](https://en.wikipedia.org/wiki/Serial_communication) library written in TypeScript for [Deno](https://deno.land) without any third party modules.

This library provides an interface for the communication with serial devices and **doesn't use any third party modules**. It uses C++ functions which are compiled to [WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly). These functions are then loaded by Deno to establish a serial connection and talk to the devices.

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/info.svg">
>   <img alt="Info" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/info.svg">
> </picture><br>
>
> We are currently migrating from our [old repository](https://github.com/TypeScriptPlayground/Serial).

## Features
- Communication with serial devices.
- Create multiple serial connections at the same time.
- List available ports and their properties (if available).
- Set timeouts for both reading and writing.
- All functions are async.
- Uses no third party modules.
- Works on multiple different operating systems (check [compatibility](#compatibility) for mor info).

## Compatibility
| OS      | Tested version          | Current state |
|---------|-------------------------|---------------|
| Windows | Windows 10 (x64)        | in progress   |
| Linux   | Ubuntu Server 22.04 LTS | in progress   |
| Mac     | -                       | planned       |

## Overview
The library consists of:
- The Core [Serial](https://github.com/Serial-IO/serial) library (Source Code for TypeScript Serial library)
- The low level [C++ bindings](https://github.com/Serial-IO/cpp-bindings-core) (Source Code for C++ low level bindings)

## Documentation
- [Serial](https://github.com/Serial-IO/serial): Check out the [Wiki](https://github.com/Serial-IO/serial/wiki) section on how to use the TypeScript library.
- [C++ bindings](https://github.com/Serial-IO/cpp-bindings-core): Check out the [Wiki](https://github.com/Serial-IO/cpp-bindings/wiki) section on how to use the C++ bindings.

## Community/Discussions
Get in touch with the community [here](https://github.com/orgs/Serial-IO/discussions) or provide feedback and suggestions for the library.

## Credits
- Big thanks goes out to [@Katze719](https://github.com/Katze719) who wrote most of the C++ files and functions!
- Thanks to [@AapoAlas](https://github.com/aapoalas) for the great support and help on the [Deno Discord](https://discord.gg/deno)!
- Thanks to [@Dj](https://github.com/DjDeveloperr) for the inspiration on how to write such a library!

## Licence
- [Serial](https://github.com/Serial-IO/serial): GPLv2.0. Check [LICENSE](https://github.com/Serial-IO/serial/blob/main/LICENSE) for more details.
- [C++ bindings](https://github.com/Serial-IO/cpp-bindings): GPLv2.0. Check [LICENSE](https://github.com/Serial-IO/cpp-bindings/blob/main/LICENSE) for more details.

Feel free to contribute to this project.

Copyright 2025 © Paul & Max
