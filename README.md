# CNTRLLD ClearVox — beta

Room and feedback removal for live vocals: everything but the voice goes, the voice stays as it was.

**Download:** the newest installer is under [Releases](../../releases/latest) (`ClearVox-<version>.pkg`).

## Install

1. Download `ClearVox-<version>.pkg` and double-click it.
2. Choose VST3 and/or Audio Unit. The installer is signed and notarised by Apple, so it opens without warnings.
3. Start your DAW and let it rescan its plug-ins. ClearVox appears under **CNTRLLD**.

macOS 11 or newer, Apple Silicon and Intel. Installs to `/Library/Audio/Plug-Ins/VST3` and `/Library/Audio/Plug-Ins/Components`.
Not seeing the Audio Unit in Logic? Log out and back in once.

## Using it

- **Clean** — how much is taken away; 100 % is everything but the voice.
- **Live** (0 ms) · **Live+** (5 ms, a little cleaner) · **Studio** (for post-production; your DAW compensates the latency).
- **Gate** — on for vocals on a loud stage, off for speech.
- **Hear removed** — listen to only what is taken away.

What changed: see [CHANGELOG.md](CHANGELOG.md).

This is a beta. Feedback is welcome.

## Uninstall

Delete `ClearVox.vst3` from `/Library/Audio/Plug-Ins/VST3` and `ClearVox.component` from `/Library/Audio/Plug-Ins/Components`.
