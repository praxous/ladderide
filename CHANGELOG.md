# Changelog

All notable changes to LadderIDE are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Pro activation: the store product identifiers ship in the first update after
  Pro purchase opens. A 1.4.0 install runs as Sim until then.

## [1.4.0] — 2026-10-18

First public release. One installer, two modes: Sim (free) without a key, Pro with one.

### Added
- Ladder canvas with named, typed tags: contacts, coils, one-shots, timers, counters,
  compare, math, CPT, SCP, PID, COP/CPS, convert, sequencers, bit shift, FIFO/LIFO,
  motion axes (stepper, servo, DC).
- Reusable MBS logic blocks and UDS struct types, portable as `.mbs` / `.uds` files.
- Offline simulator with force, toggle and trend recording.
- Device and shield catalog: I2C sensors, DAC/PWM outputs, Ethernet, serial buses.
- Pro: Arduino sketch generation, compile and upload with the bundled arduino-cli
  (Uno/Nano/Mega board support included, offline); Get Online live values over serial;
  EtherNet/IP and Modbus TCP server + client, Modbus RTU and DF1 masters (MSG).
- Help ▸ Quick Start, DF1 Setup Guide, a teaching series of example projects,
  the licence agreement and third-party notices from Help ▸ About.

### Notes
- Not yet code-signed: Windows SmartScreen may warn on first run (More info ▸ Run anyway).
- Versions 1.1–1.3 were private test builds and were never published.

[Unreleased]: https://github.com/praxous/ladderide/releases
[1.4.0]: https://github.com/praxous/ladderide/releases/tag/v1.4.0
