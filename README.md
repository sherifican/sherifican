# Micah — Applied AI Systems & DevEx
Drummer, systems builder, AI systems architecture & hardware enthusiast.

 
I build and operate multi-node AI workflows, workflow optimizations, custom developer tooling, and the verification layers that keep them reliable.

My core focus is practical execution: routing tasks by cost and capability rather than defaulting to the most expensive cloud models, running local inference on dedicated hardware, and writing deterministic guards around probabilistic systems.

---

### Core Repositories

* **[Agent-FleetOps](https://github.com/sherifican/Agent-FleetOps)**  
Custom multi-agent orchestration built from scratch (no CrewAI, LangGraph, or any framework). Counters off-the-shelf failure modes — error cascades, argument loops, unverified agent trust — with mutation-proven drift guards, deterministic apply, driver-lock serialization, and verifier-first review panels. Routing decisions are made against real measured throughput per hardware tier, via a multi-box telemetry pipeline whose data is in the repo — not vendor benchmarks. A 364-test hermetic monitor proves every guard can fail. Validated in production via ParaKit (~3,000 clones)

  <a href="https://github.com/sherifican/Agent-FleetOps">
    <img src="https://raw.githubusercontent.com/sherifican/Agent-FleetOps/main/docs/banner.png"
         alt="Agent-FleetOps — operational tooling and verification infrastructure for multi-agent fleets"
         width="100%">
  </a>


* **[ParaKit](https://github.com/sherifican/ParaKit-Open_Source)**  
An open-source desktop Drum-Charting tool / audio/MIDI studio (neural stem splitting, spectral transcription, chart editing) built in Python 3.12. It serves as the live production testbed for my multi-agent locking protocols, release-upgrade harnesses, and AST-extracted test suites.


   <a href="https://github.com/sherifican/ParaKit-Open_Source">
    <img src="https://raw.githubusercontent.com/sherifican/ParaKit-Open_Source/main/parakit_repo_banner.svg"
         alt="ParaKit — Custom Song Creator for Paradiddle &amp; Clone Hero: all-in-one drum chart tool"
         width="100%">
  </a>
