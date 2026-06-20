# Sojemand

I build local evidence systems, semantic databases and LLM-assisted research
tools.

My main project is **The Ontology Machine**: a local-first Windows system for
turning document collections into evidence-bound SQLite corpus databases, then
working with them through Query, Ontology and Taxonomy Agents.

The core idea is simple:

```text
documents -> evidence artifacts -> semantic corpus DB -> ontology lenses -> computable knowledge work
```

The project grew from a personal research passion around theory-of-mind,
functional primitives of the human psyche, document evidence, semantic control,
and practical knowledge mining. Basically, the idea of why not try to condense
thought? Since human thoughts are elusive, but code is not, the next obvious
candidate is AI. And since AI is so damn fast and so good with semantics, and on
the other hand so non-persistent in its output, why not capture its thoughts and
turn them into something useful?

## Current Main Project

### The Ontology Machine

A local Windows application for:

- document ingestion
- source-grounded semantic search
- SQLite corpus databases
- evidence backlinks to page images
- Semantic Release based taxonomy/projection control
- ontology lens creation
- peer-review style knowledge mining
- local agent workflows

It is not a cloud app. It is not a thin chat wrapper. It is an attempt to make
non-deterministic model work inspectable, evidence-bound and computable.

## What I Care About

- human and machine co-reasoning
- evidence-bound AI systems
- local-first tools
- semantic control layers
- knowledge mining
- document intelligence
- digital memory architectures
- systems that expose uncertainty instead of hiding it

## Links

- The Ontology Machine repository: https://github.com/Sojemand/The-Ontology-Machine
- Latest release: https://github.com/Sojemand/The-Ontology-Machine/releases/latest

## Research

I am the author of *Making Human Suspicion Computable*, a position paper on evidence-bound knowledge mining, ontology lenses, and human-AI co-reasoning.

- Paper: [Making Human Suspicion Computable](https://philpapers.org/rec/WEIWMK)
- ORCID: 0009-0002-1789-965X

### Toward A Workable Digital Psyche

The larger goal behind this work is a practical software path toward a workable
digital psyche.

By "digital psyche" I mean a persistent, structured, evidence-bound memory and
state-shaping architecture that can influence an agent's future behavior over
time.

The core claim is architectural:

```text
stable agent development requires a persistent memory ground state,
dynamic retrieval weights, state shaping, traces, and consolidation.
```

Prompts, context windows, and vector retrieval can all be useful parts of this
system. The larger architecture gives them a durable memory substrate and a
recursive development loop.

A workable digital psyche requires:

- persistent semantic memory
- inspectable evidence
- taxonomy
- ontology layers
- ontology lenses as retrieval frames
- dynamic retrieval
- salience weighting
- state-shift weighting
- action traces
- consolidation
- versioned memory evolution

The key move is that ontology layers become structured retrieval weights. In
combination, those weights determine which parts of memory become active and how
strongly they can shape the next state.

The practical loop looks like this:

```text
raw human material
-> semantic ingestion
-> taxonomy
-> ontology layers
-> retrieval weights
-> evidence-bound memory core
-> dynamic retrieval
-> state shaping
-> output or action
-> trace logging
-> consolidation
-> updated memory core
```

The important part is recursion:

```text
memory shapes behavior
behavior leaves traces
traces are consolidated into memory
memory changes future behavior
```

In a minimal state model:

```text
x(t0) = current agent state
m(t0) = persistent semantic memory core
s(t)  = current input

r(t)  = R(s(t), x(t0), m(t0))
x(t1) = shape(x(t0), r(t), ontology_layers, lenses, salience)
a(t)  = action_or_response(x(t1))
e(t)  = trace(a(t), outcome, context)
m(t1) = L(m(t0), e(t))
```

Where:

```text
R       retrieval from memory
r(t)    activated memory packet
layers  retrieval weights and state-shift parameters
lenses  active ontology perspectives and retrieval frames
L       consolidation back into memory
```

The Ontology Machine implements the first major part of this architecture: the
persistent semantic memory core.

It already provides:

- local corpus ingestion
- artifact-preserving processing
- rebuildable local databases
- taxonomy generation
- ontology layer construction
- source and page references
- evidence atoms
- semantic release artifacts
- inspectable database surfaces
- queryable semantic structures
- local-first reproducibility

This means large, messy human material can already be transformed into a
structured, source-bound, inspectable memory substrate.

The next architectural layer is the runtime bridge between memory and behavior.
That layer activates the memory core through:

- taxonomy-guided retrieval
- ontology-layer weighting
- ontology lens selection
- salience weighting
- state-shift coupling
- bounded memory injection
- reflective retrieval passes
- delegated deep memory search
- trace-to-memory consolidation
- personality ground-state design

Ontology layers are the bridge between stored meaning and dynamic behavior. They
can be interpreted as structured weighting surfaces over the memory core. Each
layer changes what the retrieval system considers important, how strongly a
memory packet is activated, and which kind of state shift it can produce.

In simplified form:

```text
memory node
-> ontology layer membership
-> lens activation
-> retrieval weight
-> salience score
-> coupling into x(t1)
```

The state shift emerges from the combined weights of several active layers:

```text
x(t1) = x(t0)
        + weighted_memory(r)
        + lens_bias(active_lenses)
        + ontology_layer_coupling(active_layers)
        + salience_policy(context_budget)
```

Ontology lenses sit one level above the layers. They select or combine weighting
surfaces for a specific interpretive frame.

Examples:

```text
continuity lens       what keeps the agent coherent across time
moment lens           what the current situation feels like from inside
self-relation lens    how the agent relates to itself in this moment
direction lens        where attention, expectation, and memory are pulling
stability lens        what keeps a state stable or makes it collapse
meaning lens          which interpretations become likely or dominant
pressure lens         what feels costly, urgent, risky, or important
policy lens           which learned priorities shape action and response
```

Software-wise, a lens is a small retrieval and weighting program over the
corpus. It decides which evidence, memories, and semantic patterns should count
for the current turn.

```text
current input
-> active lens
-> query relevant taxonomy terms and ontology layers
-> retrieve source-bound memory packets
-> apply lens-specific weights
-> produce a compact state-shaping packet
-> inject that packet into the next model call
```

A personality ground state is the first persistent memory state from which an
agent's behavior is allowed to emerge.

It is a designed memory substrate:

```text
ground_state = {
  corpus,
  taxonomy,
  evidence_atoms,
  ontology_layers,
  ontology_lenses,
  salience_weights,
  state_shift_weights,
  retrieval_modes,
  consolidation_rules
}
```

Good ground-state design defines:

- what kinds of memories exist
- how they are grouped
- which motifs and conflicts are salient
- which ontology layers carry strong retrieval weight
- which lenses can be activated
- which evidence supports claims
- which state shifts are encouraged by recurring memory patterns
- which themes are stable identity anchors
- which themes are allowed to drift
- which outputs should become future memory

The result is a software architecture for persistent, inspectable,
evidence-bound agent continuity.

The end goal is a full dynamic psyche loop:

1. Build a persistent memory ground state from human material.
2. Expose it through taxonomy, ontology layers, and ontology lenses.
3. Retrieve context dynamically from that memory.
4. Use ontology-layer weights to shape the current agent state.
5. Record actions, decisions, conversations, and outcomes as traces.
6. Consolidate important traces back into the memory core.
7. Let the system develop over time without losing source grounding.

This endgame should not be read as a claim that such a system is already cheap
and effortless to build today. In a technical sense, much of it could be built
now, but with significant token costs and latency. The more useful framing is
that this is a workable path toward systems that become economically viable in a
future where model latency, token costs, and context windows provide a more
fertile ground for architectures like this.

In no way do I claim that the proposed architecture will look exactly as
described. The Ontology Machine itself went through many iterations before it
reached its workable state, so it is reasonable to assume that the final shape
of this architecture would differ in detail. Generally, however, there is no
fundamental barrier, computational or hardware-related, that would prevent such
a system from becoming reality.
