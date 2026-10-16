# ClearVox changelog

Newest first. Every version is a download under [Releases](https://github.com/cntrlld/ClearVox-beta/releases).

## 0.5.21 — 16 October 2026
- First public beta installer: one signed and notarised `.pkg` for Apple Silicon and Intel, VST3 and Audio Unit.
- **Mode:** Live (0 ms), Live+ (5 ms, cleaner) and Studio (look-ahead for post-production; the DAW compensates the latency). One at a time.
- **Gate** on/off, shown in the Removing meter.
- Lower CPU: the Studio and Live+ look-ahead engine only listens; faster network maths; the second network runs every other step.
- The live network predicts a few milliseconds ahead, so its decisions land on time at 0 ms.
- Larger network (512): more removed, calmer, later feedback in the high end.
- Fuller low end, a little less top, and a gentle dip around 6.5 kHz where loops ring first.

## Earlier (private tests, 6–15 October 2026)
- Zero-latency engine with a trained network for room, reverb and PA return; feedback suppressor with memory; calm vocal gate; works at 44.1–192 kHz; half the CPU on a mono mic on a stereo track.
