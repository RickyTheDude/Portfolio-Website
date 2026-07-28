---
title: "Tech Twitter was something I didn't know I needed in my life"
description: "I always thought tech Twitter was just noise. Turns out I was wrong."
date: 2026-07-28
tags: ["Agentic Engineering", "AI", "Tech Twitter"]
draft: false
---

I always thought Twitter was mostly just noise for developers. Framework wars, hot takes, people arguing about whether tabs or spaces matter. I mostly ignored it.

But recently something changed. I started actually paying attention to what was coming through my feed and... it was different. People were talking about things I genuinely didn't know about. Agentic engineering, graph-based retrieval, autonomous pipelines. Stuff that wasn't in any course I'd taken. Stuff that apparently Microsoft and Stanford and Anthropic were all converging on independently.

It kind of caught me off guard honestly.

I'd been building with LLMs for a while at this point and kept running into the same wall. You ask the model something that requires connecting dots across multiple documents or reasoning through a chain of events and it just... falls apart. You get fragments. Keywords that match but no actual understanding of how things relate. Like asking "why did our metrics drop after the migration" and getting back three paragraphs that contain the words "metrics" and "migration" but don't actually answer anything.

I assumed this was just a limitation of the technology. Something we'd have to wait for better models to solve.

Then I came across [this article from Sprytix on X](https://x.com/Sprytixl/status/2078778799064584535) and it reframed everything for me.

The core idea was simple but I hadn't seen it put this clearly before:

> "Regular RAG finds text. Graph Engineering finds relationships."

> "Same model. Same data. Completely different result — because one system searches text and the other searches reality."

It clicked immediately. The problem wasn't the model. The problem was that I was giving it flat chunks of text and expecting it to reconstruct relationships that weren't explicitly stored anywhere. A knowledge graph stores those relationships directly. The model doesn't have to infer them, it just looks them up.

What really got me was that this wasn't just one person's opinion or some experimental side project. The article goes through how Microsoft built GraphRAG, how Stanford's DSPy treats the AI pipeline itself as a graph of connected modules, how Anthropic's Model Context Protocol is essentially a transport layer for connecting models to structured knowledge. Three organizations. Three completely independent research paths. All landed in the same place.

One line in particular stuck with me:

> "The right graph beats the bigger model. Every time."

I've been thinking about that a lot since. Because the instinct whenever something breaks is to reach for a better model. More parameters, smarter architecture, newer release. But apparently the system around the model matters more than the model itself. Build the right graph and even a smaller model performs better.

That's a fundamentally different way to think about this stuff.

I don't think I would have stumbled onto any of this through the usual channels. No tutorial would have framed it this way. No course would have pointed me to the GraphRAG paper or the Stanford scaling laws research or the Anthropic MCP docs all in one place. It just showed up in my feed one morning and now I can't stop thinking about it.

I guess that's what I didn't expect about tech Twitter. At its best it's not noise at all — it's practitioners sharing what they're actually learning in real time, before it shows up anywhere else. You just have to know whose signal to follow.

Still figuring that part out. But I'm paying more attention now.
