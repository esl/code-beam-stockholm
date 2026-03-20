---
audience:
- intermediate
tags: []
title: AI-Assisted Development of a High-Performance Market Data Platform on the BEAM
speakers: _participants/AlinaPopova.md

---
EXANTE is a global fintech brokerage that provides access to thousands of financial instruments worldwide through a single, unified platform — including stocks, ETFs, bonds, futures, options, and currencies. This talk explores the practical use of AI-assisted code generation tools and analysis in the development of TickDB, a high-performance system for real-time storage and processing of market data, one of Exante services. TickDB ingests, aggregates, and serves tick-level data including quotes, trades, bonds, options, and fundamental indicators, with support for time-based aggregations from minutes to days. We will share how AI tools are applied to generate production-ready code, analyze complex Erlang codebases, and automatically create internal common test suites, improving development speed, code quality, and long-term maintainability in a distributed, data-intensive system built on RocksDB.


**Talk objectives:**

* 1. Present real-world applications of AI-driven code generation in a production-grade, high-loaded market data system, including the generation of Erlang modules, application.
* Demonstrate the use of AI for deep code analysis and comprehension in large Erlang/OTP codebases, helping engineers understand complex logic, identify architectural patterns, and support safe refactoring in long-lived distributed systems.
* Explain automated generation of internal Common Test suites using AI, focusing on improving test coverage, logic, consistency, and developer productivity without compromising correctness or maintainability.
* Discuss validation strategies, limitations, and risks of AI-generated code, including review workflows and correctness guarantees.
* Share practical lessons learned from integrating AI tools into an existing high-performance data platform, highlighting what worked, what failed, and how AI can realistically augment—not replace—experienced engineers.

**Target audience**

* developers from junior to senior level
