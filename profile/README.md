# Serial
[![Build binaries]](https://github.com/TypeScriptPlayground/Serial/actions/workflows/build.yml)

<a href="https://deno.land"><img align="right" src="https://deno.land/logo.svg" height="150px" alt="the deno mascot dinosaur standing in the rain"></a>

A [serial](https://en.wikipedia.org/wiki/Serial_communication) library written in TypeScript for [Deno](https://deno.land) without any third party modules.

This library provides an interface for the communication with serial devices and **doesn't use any third party modules**. It uses C++ functions which are included in a [dynamic link library](https://de.wikipedia.org/wiki/Dynamic_Link_Library) or [shared object](https://en.wikipedia.org/wiki/Library_(computing)#Shared_libraries). These functions are then loaded by deno to establish a serial connection and talk to the devices.
