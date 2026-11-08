# Manu Jimenez

Audio engineer building real-time tools, automation, and open-source fixes.

I have spent 25 years working across touring, live production, broadcast, mixing, mastering, and Dolby Atmos. I came to software through the systems I use every day: when a production problem keeps coming back, I build the tool I wish I had.

Most of my work sits where audio meets software: low-latency processing, synchronization, hardware control, capture and playback, and operational tooling that has to recover cleanly under show conditions.

I use AI as part of my development workflow, but I own the problem selection, testing, review, and final result. I care more about fixes that survive real use and maintainer review than code volume.

[manuaudio.com](https://manuaudio.com/)

## Open source

My upstream contributions have landed in projects including:

- [Omarchy](https://github.com/omacom/omarchy) and [Omarchy Packages](https://github.com/omacom/omarchy-pkgs)
- [Surge XT](https://github.com/surge-synthesizer/surge) and its supporting audio libraries
- [TagLib](https://github.com/taglib/taglib)
- [Orca](https://github.com/stablyai/orca)

The work includes parser hardening, bounds validation, undefined-behavior fixes, CI repairs, and Linux desktop integration. I keep patches narrow, add focused regression coverage, and stay involved through review and merge.

<!-- merged-upstream:start -->
## Merged upstream

**42 pull requests merged** into 15 projects since August 2026, median 1.6 days to merge, 11 open now. [Every one of them](https://manuaudio.com/open-source/).

| Project | Merged |
|---|---|
| [omacom/omarchy](https://github.com/omacom/omarchy) | 9 |
| [surge-synthesizer/surge](https://github.com/surge-synthesizer/surge) | 9 |
| [taglib/taglib](https://github.com/taglib/taglib) | 5 |
| [surge-synthesizer/tuning-library](https://github.com/surge-synthesizer/tuning-library) | 3 |
| [bitfocus/companion-module-waves-lv1](https://github.com/bitfocus/companion-module-waves-lv1) | 3 |
| [surge-synthesizer/sst-basic-blocks](https://github.com/surge-synthesizer/sst-basic-blocks) | 2 |
| [surge-synthesizer/sst-effects](https://github.com/surge-synthesizer/sst-effects) | 2 |
| [surge-synthesizer/sst-plugininfra](https://github.com/surge-synthesizer/sst-plugininfra) | 2 |

**In review now**

- [omacom/omarchy#14001](https://github.com/omacom/omarchy/pull/14001) Fall back to glcore in RetroArch when no GPU provides Vulkan
- [omacom/omarchy#14038](https://github.com/omacom/omarchy/pull/14038) Only count this user's hyprsunset as running for night light
- [omacom/omarchy#14182](https://github.com/omacom/omarchy/pull/14182) Keep Taildrop home shorthand on literal directory boundaries
- [omacom/omarchy#17520](https://github.com/omacom/omarchy/pull/17520) Let PipeWire follow the source's sample rate
- [ExistentialAudio/BlackHole#899](https://github.com/ExistentialAudio/BlackHole/pull/899) Make the shared IO state in DoIOOperation atomic
- [bjarneo/cliamp#698](https://github.com/bjarneo/cliamp/pull/698) Fix: The radio playlist are limited to 200 tracks
- [bjarneo/cliamp#700](https://github.com/bjarneo/cliamp/pull/700) Fix: keep stored playlist order when shuffled
<!-- merged-upstream:end -->

## Audio systems

- **Real-time audio:** low-latency engines, multitrack capture and playback, plugin hosting, metering, and loudness measurement
- **Synchronization:** LTC and MTC generation and capture, drift measurement, drop-frame handling, and timecode-driven playback
- **Console and hardware integration:** digital mixing console control, automation, network audio transport, and control-surface protocols
- **Production tooling:** systems tested against real hardware and show conditions, not only unit tests

## Working stack

Swift · Core Audio · AudioUnits · SwiftUI · C++ · Go · Rust · TypeScript · Python · Linux
