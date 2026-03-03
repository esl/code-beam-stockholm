---
audience:
- Introductory and overview
tags: []
title: Low Power Wireless Sensors with AtomVM
speakers:
- _participants/Davide-Bettio.md

---
AtomVM makes it possible to run Erlang, Elixir and Gleam on tiny, resource constrained devices by executing bytecode from compiled .beam files on supported targets, while remaining a separate VM from the traditional BEAM.

In this talk, I will show why AtomVM can be a great fit for building wireless sensors: you can write small firmware that reads real sensor hardware, structure the application using the tools we already love, and then deliver data where it matters.

We will look at practical wireless delivery options that fit real deployments, for example long range LoRa for field data collection, or Wi-Fi for publishing data to a broker using MQTT or for home automation, focusing on what is feasible on AtomVM and what trade offs you should expect.

To keep things grounded, I will walk through a working end to end example of a small sensor node, showing how to go from reading a sensor to data arriving somewhere useful.

**Talk objectives:**

* You will learn how the Erlang ecosystem can power wireless sensors and how you can build one, even for simple everyday tasks like home automation.
