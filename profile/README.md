# Serial-Link

<a href="https://deno.land"><img align="right" src="https://deno.land/logo.svg" height="150px" alt="the deno mascot dinosaur standing in the rain"></a>

A [serial](https://en.wikipedia.org/wiki/Serial_communication) library written in TypeScript for [Deno](https://deno.land) without any third party modules.

This library provides an interface for the communication with serial devices and **doesn't use any third party modules**. It uses C++ functions which are included in a [dynamic link library](https://de.wikipedia.org/wiki/Dynamic_Link_Library) or [shared object](https://en.wikipedia.org/wiki/Library_(computing)#Shared_libraries). These functions are then loaded by Deno to establish a serial connection and talk to the devices.

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
- The Core [Serial-Link](https://github.com/Serial-Link/Serial-Link) library (Source Code for Serial library)
- The low level [C++ bindings](https://github.com/Serial-Link/Serial-Link) (Source Code for C++ low level bindings)

## Credits

- Big thanks goes out to [@Katze719](https://github.com/Katze719) who wrote most of the C++ files and functions!
- Thanks to [@AapoAlas](https://github.com/aapoalas) for the great support and help on the [Deno Discord](https://discord.gg/deno)!

## Licence
Apache-2.0. Check [LICENSE](./LICENSE) for more details. Feel free to contribute to this project.

Copyright 2023 © Max
