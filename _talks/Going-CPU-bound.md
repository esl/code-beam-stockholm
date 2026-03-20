---
audience:
- intermediate
tags:
- CPU
- async_stream
- concurrency

title: A safer Elixir
speakers:
- _participants/David-Klemenc.md

---
I’m going to present findings from four months of performance optimisations where our team was tasked with creating a transaction service that can handle 40_000 transactions per second on a single node. I'll present our team's process and the insights we gained along the way. Much of the performance came from general DB optimisations (Postgres), but I'll focus on simulating traffic and on critical characteristics of standard library functions. Before achieving the desired performance on the transaction server it was necessary to simulate an appropriate amount of traffic with a distribution similar to our current one.

**Talk objectives:**

We'll go from setting up a test server with a dummy endpoint (that does nothing but return 200 OK) to serving 250_000 requests per second to that endpoint. Along the way, we'll cover changes that delivered from 40% better performance to 10x increases.
