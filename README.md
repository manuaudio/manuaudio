# Manu

Professional audio software for macOS.

I work on real-time audio systems for live sound and broadcast — environments where the software runs for twelve hours straight and a single dropout is unacceptable. Most of that is Swift against Core Audio and AudioUnits, with a lot of attention paid to the parts that fail quietly: clock drift, sample-accurate timing, timecode correctness across midnight and drop-frame boundaries.

### Focus

**Real-time audio** — low-latency engines, multitrack capture and playback, plugin hosting, metering and loudness measurement.

**Synchronisation** — LTC and MTC generation and capture, drift measurement against wall clock, drop-frame handling, timecode- and time-of-day-driven playback.

**Console and hardware integration** — digital mixing console control and automation, network audio transport, control-surface protocols.

**Tooling** — build and test infrastructure for audio software, where correctness has to be proven on real hardware rather than inferred from a passing unit test.

### Open source

Contributor to [Orca](https://github.com/stablyai/orca), an agent development environment for running coding agents in parallel.

### Stack

Swift · Core Audio · AudioUnits · SwiftUI · TypeScript · Python
