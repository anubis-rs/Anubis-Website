---
layout: page
title: About Anubis
---

Anubis is a PS Vita emulator written in [Rust](https://github.com/rust-lang). It uses [wgpu](https://github.com/gfx-rs/wgpu) for rendering and [SPIR-V](https://www.khronos.org/opengl/wiki/SPIR-V) as shader definition language.

It comes with:
 - Custom written Arm-Cortex A9 JIT Compiler
 - GPU emulation
 - and much more

You can find the source code for Anbuis at GitHub:
[Anubis](https://github.com/anubis-rs/anubis)

Anubis is not only a PS Vita emulator but also a growing community that deals with vita hacking/homebrew.
Join our community [here](https://discord.gg/Kphvzgwdkz)

## Why Rust?
Rust is a systems programming language that places a lot of emphasis on security and accuracy.
Because of these facts I decided to use this language.
In addition, it also has a lot to offer with its great ecosystem

## WGPU
[wgpu](https://github.com/gfx-rs/wgpu) is an implementation of the WebGPU API, targeting both native and Web. I decided to use it, since it already provides support to the target platforms I had in mind implementing the CPU JIT Compiler for.
For shaders we will use the intermediate shader definition language [SPIR-V](https://www.khronos.org/opengl/wiki/SPIR-V).
In addition we will use [winit](https://github.com/rust-windowing/winit) for window management.


## Installation
TODO

## Credits
TODO
