# ClearVox changelog

Newest first. Every version is a download under [Releases](https://github.com/cntrlld/ClearVox-beta/releases).

## 0.5.26 — 24 October 2026
- The Hear removed button is gone: the interface is Live / Live+ / Studio, Gate and Bypass.

## 0.5.25 — 20 October 2026
- ClearVox now has a 30-day trial with nothing held back. After that, a licence keeps it running: €49.95 during the beta, every update included. Paste the licence in the licence line at the bottom right.
- The same licence system as SPECTRA: one licence for your computers, checked on your own machine. A licence for all CNTRLLD plug-ins works too.

## 0.5.24 — 16 October 2026
- Clean now goes to 120 %. Up to 100 % nothing changed (100 % is still the default; double-click returns to it). From 100 to 120 % extra protection against rings in the high end fades in: a deeper dip around 6.5 kHz and a little less top. At 120 % rings at 5-8 kHz start about 3 dB later than at 100 %; the voice gets a bit duller. The value turns amber above 100 %.

## 0.5.23 — 16 October 2026
- Live: a little less top, like De-Feedback, so rings in the high end stay away longer: in the show test 5-8 kHz rings start 2 dB later (+8.5 instead of +6.5), with about the same colour as De-Feedback.
- Live+ keeps its open top.
- Studio is now fully open (no top reduction at all): there is no feedback loop to fear in post-production.

## 0.5.22 — 16 October 2026
- Safety ceiling: a clipped input can no longer push the output over 0 dBFS (it reached +3.8 dBFS before). A normal voice is untouched.
- Gate is off by default.
- Switching Live / Live+ / Studio fades out and back in (no click).
- Bypass now lines up in Live+ and Studio (the dry signal is delayed by the same latency).

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
