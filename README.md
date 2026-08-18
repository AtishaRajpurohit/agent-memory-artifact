# Agent Memory — Interactive Teaching Artifacts

Three self-contained, click-through artifacts built for a session on agent
memory at the SupportVectors AI Agents Bootcamp. Each one assembles a system
one step at a time, so you can watch the behaviour rather than read a
description of it.

No install, no build step. Open the link, click or press → to advance.

---

## The artifacts

### 1. Where does it go?
**[Open →](https://USERNAME.github.io/REPO/where-does-it-go.html)**

Every piece of information an agent handles lives somewhere: the prompt, RAG,
the skill library, memory, or scratch state. This artifact builds the harness
around those five homes, then runs a quiz set inside an air crash
investigation — one piece of evidence at a time, where does it belong?

The forks are the point: contradictory witness statements, a theory that
evolves, a maintenance record that has gone stale.

*19 steps.*

### 2. Extraction, then reconciliation
**[Open →](https://USERNAME.github.io/REPO/extract-and-reconcile.html)**

The base Mem0 pipeline, assembled piece by piece. A message pair arrives, an
LLM extracts candidate facts, and each one is reconciled against what is
already stored through a tool call that picks ADD, UPDATE, DELETE, or NOOP.

The memory panel mutates live as the trace runs, which is the whole argument:
a write is a reconciliation, not an insertion. Ends on the read path.

*17 steps.*

### 3. Invalidate, don't delete
**[Open →](https://USERNAME.github.io/REPO/invalidate-dont-delete.html)**

Mem0's graph variant. An entity extractor and relations generator build typed
nodes and labelled edges; a conflict detector and update resolver handle
contradictions.

When Alice moves cities, the old edge is not deleted — it is marked invalid.
The history stays, and the graph can still answer *when* something was true.

*17 steps.*

---

## Controls

| Key | Action |
|---|---|
| `→` `Space` `click` | Next step |
| `←` | Previous step |
| `R` | Reset current screen |
| `L` | Toggle light mode |
| `N` | Speaker notes |
| `F` | Fullscreen |

Best viewed on a desktop browser — the canvas is 1920×1080 and scales to fit.

---

## Source

Chhikara et al., 2025. *Mem0: Building Production-Ready AI Agents with
Scalable Long-Term Memory.* [arXiv:2504.19413](https://arxiv.org/abs/2504.19413)

All figures and behaviour follow the paper. Framing around memory as a policy
of write / read / consolidate / forget draws on Prof. Asif Qamar's teaching at
SupportVectors.

---

Built by [Atisha Rajpurohit](https://www.linkedin.com/in/atisha-rajpurohit/).
More write-ups on [Medium](YOUR_MEDIUM_URL).
