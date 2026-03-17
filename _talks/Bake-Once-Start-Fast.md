---
audience:
- Advanced
tags:
- Embedded
- Energy
- Optimization
title: "Bake Once, Start Fast: Instant-Launch Erlang Executables"
speakers:
- _participants/peer-stritzinger.md
---
Single-file executables are great, but cold start is still dominated by ERTS loading and transforming many .beam modules, and sometimes running the JIT. Fine for servers, painful for command line tools that start often. This talk presents a packaging approach that bakes modules into their runnable in-memory form so startup can skip most loader work. We compare two paths: statically linked, relocation-patched module images, and a minimal allocator that undumps only what the Erlang runtime needs. Atom handling is part of it, but so are relocations, literals, exports, and validation. Targeting Erlang means every language in the ecosystem benefits, and leaves a path to embedded use later.

**Talk objectives:**

Attendees will learn what makes Erlang executables slow to start, how baking runnable code images can skip most module loading and optional JIT work, and which runtime structures must still be handled for correctness (atoms, relocations, literals, exports). They will leave able to judge the trade-offs and apply these ideas to build snappy command line tools today, with a clear path toward embedded use later.

**Target audience:**

This talk is for two audiences: people who enjoy digging into Erlang runtime internals and want to understand what really happens between “start” and “first function call”, and practitioners who simply want a single self-contained executable that launches fast. If you build CLIs, build tooling, CI jobs, or short-lived scripts and care about cold start latency, you will get a practical path to using the new packaging approach without needing to become a VM expert.
