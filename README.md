# Acqui Studio

Downloads and update feed for [Acqui Studio](https://acqui.studio), a macOS app that turns audio into stems, MIDI, sheet music, timed lyrics and voice conversions, running entirely on your Mac.

## Download

Get the latest disk image from the [Releases](../../releases/latest) page, or from [acqui.studio](https://acqui.studio). The app needs macOS 26 on Apple silicon.

## What is in this repository

- `updates/appcast.xml` is the [Sparkle](https://sparkle-project.org) update feed the app checks. It is signed, and the app refuses a feed that is not.
- Each release attaches a signed, notarized disk image.

This repository holds no source code. The app is proprietary.
