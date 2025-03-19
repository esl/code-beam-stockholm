---
audience: Introductory and overview
tags:
- benchmarking
- retrospective
- benchee
title: "Benchee: 9 Years of Benchmarking on the BEAM"
speakers:
- _participants/Tobias-Pfeiffer.md

---
For nearly nine years, Benchee has been the go-to tool for benchmarking in the Elixir and Erlang ecosystem. But how did it all start? What problems was it meant to solve, and did it succeed? Did the design hold up? Along the way, what surprising lessons emerged about performance on the BEAM? What mistakes were made, and what’s next for Benchee?

In this talk, I’ll take you on a journey through nearly a decade of benchmarking: the wins, the pitfalls, and the unexpected discoveries. Expect insights, anecdotes, and, of course, some benchmarks!

**Talk objectives:**

* Navigating an eco system - when do we need a new library? How do you deal with this?
* Architecture and design: Benchee has a layered approach focussing on exchangability of the layers as soon as the "contract" is honored - this has worked extremely well and there are a bunch of plugins for benchee just as I always wanted
* Benchmarking: it's not a full benchmarking talk, but I'll introduce a topic of why to benchmark, some results and share some concepts and their importance - such as warmups, the statistics, impact of GC etc.
* Open source: I'll talk about open source working and motivate people (hopefully) to participate in open source, talk about the collaboration etc.
* BEAM: We'll talk about some specialities of the BEAM, such as every process managing its own memory and messages being copied in full between processes (although they are immutable), might mention reductions. Also, of course some performance characteristics - I'll probably go to my favorite - tail recursion vs body recursion
* Failing: I think it's always important that even "fancy" library authors make mistakes, I made some with benchee and I wanna share them to normalize sharing stories of failures
