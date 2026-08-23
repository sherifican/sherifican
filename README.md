# Micah — Applied AI Systems & DevEx

I build **multi-agent AI fleets that have to keep working when nobody is watching** — and the
operational discipline that makes that survivable. Two boxes, a dozen model legs (local GPU models
behind ollama/llama.cpp plus cloud CLI agents), and the part that actually matters: the guards,
monitors, and human-gated evolution loops that catch the failures the agents themselves can't see.
The design thesis running through everything here: **a check that cannot fail is not a check.**
Every guard ships with proof it can go red — planted-mutation self-tests, teeth-provers, negative
controls — because a green light you never falsified is just a light.

**[Agent-FleetOps](https://github.com/sherifican/Agent-FleetOps)** is the operational core made
public: a 364-test hermetic fleet monitor (strict one-way pipeline, frozen dataclass contracts,
safe-default degradation), a drift-guard layer where `UNMEASURED` dominates `violation` in every
verdict, 24 generalized agent-discipline skills distilled from real failure stories, a driver-lock
protocol for concurrent AI coding agents, and a two-box throughput log — 47 measurements across 20
model tags with sample sizes and the GPU each run actually landed on, because placement is a
property of the run, not the model. The export pipeline that publishes the repo gates itself with
the same rules, and its commit history includes its own caught-and-retracted mistakes on purpose.

**[ParaKit](https://github.com/sherifican/ParaKit-Open_Source)** is the other half of the picture —
an all-in-one drum charting studio (audio→MIDI transcription, stem splitting, BPM detection, chart
generation for Paradiddle and Clone Hero) built and shipped as a real desktop product. It is also
the proving ground where the fleet earns its keep: the models do the legwork, the harness keeps
them honest. Drummer. Cat person. The fleet runs on a machine named after one of the cats.
