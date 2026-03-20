---
audience:
- beginner
tags:
- OTP
- Pheonix
- Business-Logic
title: Using OTP in Your Phoenix App
speakers:
- _participants/tonci-galic.md

---
My talk is a case study of a refactor that improved memory usage, performance, and reliability in a large Phoenix app. I think this makes for an interesting talk because we got to apply OTP patterns inside a Phoenix application in a very practical, real-world way.

Most of the codebase is a long, complex pipeline for a single API. As traffic and data grew, we hit memory issues: usage scaled poorly with load, and small increases in work caused big jumps in RAM. Our large cache lived in ETS, and for every API call we loaded this cache and did additional processing. We also used Tasks to parallelise work, which added more duplication and made memory behaviour harder to predict.

Our solution was to encapsulate large, long-lived state inside GenServers and have callers send compute requests to those processes. This change improved memory behaviour, reduced latency in our hot path, and stabilised the service in production.


**Talk objectives:**

* Why you might need to apply OTP to your pheonix app.
* Learn about some common memory-copying behaviours on the BEAM.
* Use of GenServer with DynamicSupervisor

**Target audience:**

* engineers using elixir for backend.
