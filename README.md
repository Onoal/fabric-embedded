# Fabric Embedded

Fabric Embedded is a planned standalone Onoal project for building embedded systems in Rust using Fabric-inspired systems-construction principles.

> **Status: planned — development has not started.**

## Start condition

Active development of Fabric Embedded will begin **after Onoal/Fabric reaches a stable v1 beta**.

Fabric Embedded will **not** start during Fabric's v1 alpha phase.

The separation is deliberate: the main Fabric project should first reach a sufficiently stable architecture and public language before a separate embedded ecosystem begins evolving alongside it.

## Direction

Fabric Embedded is intended to become its **own repository, runtime, and ecosystem** for constrained and embedded environments such as microcontrollers and Rust-compatible development boards.

Initial target ecosystems may include:

- ESP-class development boards
- Raspberry Pi Pico / RP-class microcontrollers
- other Rust-compatible embedded boards and MCUs
- `no_std` environments
- existing Rust embedded HALs, drivers, and runtimes

Fabric Embedded is not intended to force embedded constraints back into the main Fabric runtime. The two projects may share architectural ideas, and later may reveal genuinely shared layers, but those should only be extracted once both projects provide concrete evidence that the machinery is truly common.

For now, this repository marks the independent project boundary and future direction. The immediate priority remains Onoal/Fabric through its v1 alpha work and into a stable v1 beta.
