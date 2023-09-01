# Serial-Link

<a href="https://deno.land"><img align="right" src="https://github.com/Serial-Link/.github/blob/main/assets/profile.svg" height="150px" alt="the serial port standing in the rain"></a>

[![Deno Test](https://github.com/Serial-Link/Serial-Link/actions/workflows/deno.yml/badge.svg)](https://github.com/Serial-Link/Serial-Link/actions/workflows/deno.yml)

A [serial](https://en.wikipedia.org/wiki/Serial_communication) library written in TypeScript for [Deno](https://deno.land) without any third party modules.

This library provides an interface for the communication with serial devices and **doesn't use any third party modules**. It uses C++ functions which are included in a [dynamic link library](https://de.wikipedia.org/wiki/Dynamic_Link_Library) or [shared object](https://en.wikipedia.org/wiki/Library_(computing)#Shared_libraries). These functions are then loaded by Deno to establish a serial connection and talk to the devices.

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/info.svg">
>   <img alt="Info" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/info.svg">
> </picture><br>
>
> We are currently migrating from our [old repository](https://github.com/TypeScriptPlayground/Serial).

## Features
- Communication with serial devices.
- Create multiple serial connections at the same time.
- List available ports and their properties.
- Set timeouts for both reading and writing.
- All functions are async.
- Uses no third party modules.
- Works on multiple different operating systems.

## Overview
The library consists of:
- The Core [Serial-Link](https://github.com/Serial-Link/Serial-Link) library (Source Code for TypeScript Serial library)
- The low level [C++ bindings](https://github.com/Serial-Link/CPP-Bindings) (Source Code for C++ low level bindings)

## Documentation
- [Serial-Link](https://github.com/Serial-Link/Serial-Link): Check out the [Wiki](https://github.com/Serial-Link/Serial-Link/wiki) section on how to use the TypeScript library.
- [C++ bindings](https://github.com/Serial-Link/CPP-Bindings): Check out the [Wiki](https://github.com/Serial-Link/CPP-Bindings/wiki) section on how to use the C++ bindings.

## Credits
- Big thanks goes out to [@Katze719](https://github.com/Katze719) who wrote most of the C++ files and functions!
- Thanks to [@AapoAlas](https://github.com/aapoalas) for the great support and help on the [Deno Discord](https://discord.gg/deno)!
- Thanks to [@Dj](https://github.com/DjDeveloperr) for the inspiration on how to write such a library!

## Licence
- [Serial-Link](https://github.com/Serial-Link/Serial-Link): Apache-2.0. Check [LICENSE](https://github.com/Serial-Link/Serial-Link/blob/main/LICENSE) for more details.
- [C++ bindings](https://github.com/Serial-Link/CPP-Bindings): Apache-2.0. Check [LICENSE](https://github.com/Serial-Link/CPP-Bindings/blob/main/LICENSE) for more details.

Feel free to contribute to this project.

Copyright 2023 © Max
