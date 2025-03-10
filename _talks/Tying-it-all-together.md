---
audience:
- Introductory and overview
tags:
- Phoenix
- SaaS
- Development
title: Tying it all together
speakers:
- _participants/Lars-Wikman.md

---
Sometimes people ask for an example of an Elixir application. NervesHub is an open source application used in production at scale with a lively development history. It has been through a lot of change, a lot of evolution.

And it uses a lot of the Elixir ecosystem. Phoenix, Ecto, LiveView, Oban, thousands of WebSocket connections, an Erlang distribution cluster, a lot of PubSub, regular GenServers, PhoenixTest and much more.

This talk will give a tour of the project, focusing on interesting things, changes that have simplified the system over time. Choices that have been made and hopefully the good reasons behind them.

**Talk objectives:**

Give people a real Phoenix example to reference, study and maybe help improve?

NervesHub is not unique but tells many of the common Elixir stories very concretely. The removal of extra infrastructure that is possible thanks to the BEAM ecosystem and the power of LiveView in building a powerful SaaS product with limited means.

**Target audience:**

Web developers, Phoenix enthusiasts, Elixir developers. But mostly anyone in the ecosystem.
