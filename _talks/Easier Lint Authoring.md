---
audience:
- Advanced
tags:
- lint
- codemod
- elp
title: Easier Lint Authoring with Semantic Search and Replace in the Erlang Language Platform
speakers:
- _participants/Alan-Zimmerman.md

---
A Lint has two parts, identifying a problem, and possibly providing a fix. The first requires scanning the code for patterns that could contain a problematic occurrence, then checking each to see if it does. A fix involves changing the code, based on what has been found. This talk will show how using Semantic Search and Replace, a regex-like string to match Erlang syntax and extract interesting parts, all three of these steps can be simplified dramatically.

**Talk objectives:**
The audience will understand what SSR is, and how it can be used in practice.

**Target audience:**
People who want to write lints/diagnostics for Erlang
