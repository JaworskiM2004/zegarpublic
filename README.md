# Tilt-Reactive Clock Face (prototype)

A browser prototype of a clock face for a round ESP32 AMOLED display. Built and tested on a phone first, with the goal of porting it to the device.

## Features

- Minimalist, compass-like clock face on a pure black background (pixels off on AMOLED screens).
- Hands react to the phone's tilt (device orientation sensors).
- Shaking the phone makes the "sticker" digits fall off with simple 2D collision physics and sound.
- Battery level shown in the centre.

## Tech stack

HTML · CSS · JavaScript · DeviceOrientation / DeviceMotion APIs · Canvas · Web Audio

## Status

Prototype. The physics version was too heavy for the microcontroller in the first on-device test, so the device now uses a simpler clock. This repo keeps the web prototype.
