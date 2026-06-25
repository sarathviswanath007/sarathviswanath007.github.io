---
layout: post
title: "Prevention over correction: why I kill risk before it ships"
date: 2026-06-26
reading_time: "5 min read"
excerpt: "Most quality work happens too late — after the code is written, after the build is cut, after the risk is already baked in. Here's how I think about moving it earlier."
---

Most quality work happens too late. It happens after the code is written, after
the build is cut, after the risk is already baked into the system. By then,
testing isn't preventing problems — it's just discovering them.

Over twelve years in quality engineering, the single biggest shift in how I work
has been moving from **finding defects** to **preventing them**. This isn't a
slogan. It's a different place to stand in the delivery lifecycle.

## What "shift-left" actually means

The phrase gets thrown around a lot, usually to mean "run the tests earlier."
That's not wrong, but it misses the point. The real leverage isn't in running the
same tests sooner — it's in **partnering with Product, Engineering, and
Architecture while decisions are still cheap to change.**

A risk surfaced in a design review costs a conversation. The same risk surfaced
in production costs an incident, a rollback, and a dent in trust.

## Reading a system for where it breaks

Before I write a single test strategy, I try to read the system: where is it most
likely to fail, and what would it cost if it did? That gives me a map. The
strategy follows the map — not a generic playbook applied uniformly across
everything.

> Prevention engineered in, not inspection bolted on.

This is what I mean by context-driven strategy. Two systems that look similar on
the surface can have completely different risk profiles underneath. Forcing the
same approach onto both is how you end up with exhaustive regression suites that
still miss the thing that actually takes you down.

## Where AI fits

The newest layer of this work is figuring out where AI genuinely helps — not as a
tool bolted on, but as a shift in how the work gets done. AI can accelerate test
design, surface edge cases, and remove repetitive effort. But its output has to be
**validated, never assumed.** That's a discipline in itself, and it's where a lot
of my current thinking lives.

More on that in future posts.

---

*This is the first article on the new site. If you want to talk quality
engineering, risk, or AI in testing — [reach out](/#contact).*
