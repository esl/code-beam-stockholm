---
tags:
- elixir
- postgresql
- search
level: Addvaced
title: "Torus: Integrate PostgreSQL search into Elixir's Ecto queries"
speakers:
- _participants/Dima-Mikielewicz.md

---
Search is a fundamental part of many applications, but choosing the right approach can be challenging. This talk explores different search strategies - from full-text and similarity searches to semantic and hybrid techniques. I’ll share insights from implementing these in a large-scale codebase serving millions of users, focusing on performance, relevance, and maintainability. Finally, I’ll introduce Torus, a library designed to integrate these search methods seamlessly into Ecto, making it easier to build and refine personalized search experiences within Elixir applications.

**Talk objectives:**

* Different approaches to search: Gain a clear understanding of full-text, similarity, semantic, and hybrid search strategies, along with their strengths, weaknesses, and ideal use cases.
* Performance and Relevance at scale: See how these techniques were implemented in a large codebase serving millions of users, and discover practical tips for optimizing search speed and accuracy.
* Introducing Torus: Discover how Torus simplifies adding and customizing search features in Elixir projects, letting you get started quickly while still adapting to more advanced needs. https://github.com/dimamik/torus

**Target audience:**

This talk is for developers and engineers interested in learning about different types of search and how to effectively implement them in PostgreSQL. It will appeal to Elixir developers, PostgreSQL users, and engineering teams looking to build or optimize search functionality in their applications. Those working with large-scale databases, handling complex queries, or aiming to improve search performance and relevance will also benefit. Whether you're a backend engineer, a database architect, or simply curious about search technologies, this session will provide practical insights into integrating advanced search strategies efficiently.
