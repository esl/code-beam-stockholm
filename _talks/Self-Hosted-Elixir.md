---
audience:
- Intermediate
tags:
- BEAM
- Self-Hosting
- Elixir

title: "Self Hosted Elixir: A Pi is all you need!"
speakers:
- _participants/Sola-Aremu.md
---
Self-hosted Elixir applications offer control, cost efficiency, and privacy. This session outlines a modern workflow for deploying Elixir apps sustainably and securely, using Raspberry Pi as a server paired with Cloudflare and Coolify.

Elixir Leverages BEAM’s concurrency, fault tolerance, and real-time capabilities, amplified by Phoenix’s tooling. By combining this with Cloudflare's protections and using Coolify to manage a Raspberry Pi server, turning it into a PaaS, we can create a product with minimum recurrent running costs yet the ability to concurrently service close to a million requests.

**Talk objectives:**

**Reasons to consider Raspberry Pi **

- Low-cost, energy-efficient hardware for edge deployments.

- Perfect for small-to-medium apps (e.g., IoT, personal projects, microservices).

- Full control over data with no cloud vendor lock-in.

** Cloudflare’s Role **

- Tunnels: Securely expose apps on Raspberry Pi without port-forwarding or static IPs.

- DNS & CDN: Mask Pi’s residential IP and optimize global traffic.

- Zero Trust: Protect admin interfaces (e.g., Coolify dashboard).

** Coolify on Raspberry Pi **

- Deploy Coolify (open-source PaaS) on Pi via Docker—supports ARM64.

- Automate Elixir app deployments using Git: Build mix release or Docker images directly on the Pi.

- Manage databases (Postgres/Redis), cron jobs, and SSL (via Cloudflare).

**Target audience:**

BEAM Enthusiasts, Hobbyists, Engineers, CTOs
