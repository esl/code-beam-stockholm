---
audience:
- Introductory and overview
tags:
- Concurrent
- Resilient
title: Web Apps in Erlang Are Actually Simple
speakers:
- _participants/Daniel-Widgren.md
- _participants/Niclas-Axelsson.md


---
Erlang is known for telecom systems, distributed databases, and extreme fault tolerance.

But simple web apps?
Not really.
In this talk, we challenge the idea that building web applications in Erlang is complicated or overly academic. Using Nova, we’ll show how straightforward it can be to build a modern web app — with routing, templates, and JSON APIs — without fighting the framework or drowning in OTP abstractions.

Then we’ll look at what makes Erlang fundamentally different from most web platforms: every request runs in its own lightweight process. Crashes are isolated. Concurrency is the default. Fault tolerance isn’t bolted on — it’s the foundation.

Just processes, isolation, and supervision.
If you’ve ever felt that web development on the BEAM is “too much OTP” or too heavy for everyday applications, this talk aims to change your perspective.
Web apps in Erlang are not only possible.
They’re actually simple.

**Talk objectives:**

* How to build a simple, modern web app in Erlang using Nova
How routing, templates, and JSON APIs work — without OTP complexity
Why the BEAM model (one lightweight process per request) simplifies concurrency
How crash isolation and supervision give fault tolerance “for free”

**Target audience:**

* Backend developers curious about Erlang/BEAM
* Elixir developers who want to understand Erlang at a deeper level
* Web developers interested in high-concurrency or fault-tolerant systems
* Engineers working with distributed systems
* Developers who think “Erlang is too heavy/academic for web apps
