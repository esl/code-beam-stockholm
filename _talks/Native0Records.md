---
audience:
- intermediate
tags:
- records
- evolution
- performance
title: Native Records
speakers:
- _participants/Bjorn-Gustavsson.md
---
Traditional Erlang records are a compile-time convenience; at runtime they are just tuples.

Erlang/OTP 29 introduces native records, a new data type distinct from tuples and maps. In this talk, we'll walk through the motivation behind native records, the design constraints, and practical trade-offs. We'll look at the performance characteristics of the current implementation and how we plan to improve it in OTP 30 and beyond.



**TALK OBJECTIVES:**

To give an understanding of the difference between native records and traditional tuple records; what to expect about performance in the current implementation and in the future.
