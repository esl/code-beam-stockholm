---
audience:
- Advanced
tags:
- Embedded
- Energy
- Optimization
title: "Squeezing the BEAM into 16MB: Surviving on Energy Harvesting with GRiSP nano"
speakers:
- _participants/peer-stritzinger.md
---
Erlang was designed for fault tolerance, not fitting into tiny memory footprints on energy-starved embedded systems. But what happens when you push it into just 16MB of RAM, run it on an RTEMS real-time OS, and power it from temperature gradient energy harvesting?

In this talk, we’ll dive into the challenges and solutions of making the full Erlang runtime, OTP, a TCP/IP stack, and USB support work under extreme constraints. We’ll explore the brutal trade-offs in memory usage, optimizing the boot process for minimal energy consumption, and the unexpected quirks of running Erlang on hardware where every millijoule counts.

Along the way, we’ll break down how GRiSP nano boots from a cold start, how energy availability affects system initialization, and what we learned from pushing BEAM into places it was never meant to go.

If you’re curious about embedded Erlang, extreme resource constraints, or just want to see how far you can push the runtime, this talk is for you.

**Talk objectives:**

- How to fit Erlang/OTP, networking, and I/O into 16MB of RAM
- Lessons from optimizing BEAM’s boot process for minimal energy usage
- How RTEMS and Erlang interact in low-power environments
- Practical insights into energy harvesting for embedded systems

**Target audience:**

Embedded Systems Developers – Engineers working with constrained hardware who want to explore how Erlang/OTP can be adapted for resource-limited environments.
• BEAM Enthusiasts & Erlang/Elixir Developers – Anyone curious about pushing the BEAM to its limits and running it in unconventional places.
• IoT & Low-Power Computing Engineers – Those interested in energy harvesting, power-aware system design, and making software work on ultra-low-power hardware.
• Distributed Systems & Real-Time Computing Experts – Developers who want to understand how Erlang interacts with RTEMS and real-time constraints.
• Researchers & Experimenters – People working on sustainable computing, extreme edge computing, or novel applications of functional programming in embedded systems.
