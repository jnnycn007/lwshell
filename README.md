# Lightweight shell

LwSHELL is a lightweight, platform independent, command line shell for embedded systems.
It targets communication with embedded systems from remote terminal to quickly send commands and to retrieve data from the device.

[Open documentation](https://docs.majerle.eu/projects/lwshell/)

## Features

* Written in C (C11), compatible with `stdint.h` data types
* Lightweight command-line shell for embedded systems
* Platform independent and very easy to port
* No dynamic (heap) memory allocation, with runtime command registration up to a compile-time configurable limit
* Optional static, ROM-based command tables as an alternative to runtime registration, to save RAM
* Supports quoted arguments to allow spaces inside a single parameter
* Basic line editing with backspace and delete key support
* Optional `listcmd` command to list all registered commands
* Optional output callback to send shell responses back to the application
* Multiple independent shell instances through `_ex` API functions
* Helper macros to parse arguments as `int`, `long` or `double`
* Highly configurable
* Simple help-text with `cmd -h` option
* User friendly MIT license

## Contribute

Fresh contributions are always welcome. Simple instructions to proceed:

1. Fork Github repository
2. Follow [C style & coding rules](https://github.com/MaJerle/c-code-style) and use `clang-format` to format the code
3. Create a pull request to `develop` branch with new features or bug fixes

Alternatively you may:

1. Report a bug
2. Ask for a feature request
