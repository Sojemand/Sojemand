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

#### One Sentence

The Ontology Machine is a semantic memory engine for future agents: it turns
large, messy human material into a persistent, inspectable, evidence-bound
memory core that can later shape dynamic, evolving digital personalities.

#### The Endgame

The goal is to define and build a practical software path toward a workable
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

#### Required Components

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

#### The Practical Loop

The larger architecture can be described as a software loop:

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

That is the practical path from static agent prompts toward dynamic, evolving
digital personalities.

#### State View

In a minimal state model:

```text
x(t0) = current agent state
m(t0) = persistent semantic memory core
s(t)  = current input
```

The runtime loop:

```text
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
salience weighting, coupling strength, and budget control
L       consolidation back into memory
```

The software architecture is stateful:

```text
x(t0) -> memory activation -> x(t1) -> trace -> m(t1)
```

#### What The Ontology Machine Already Provides

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

The Ontology Machine proves that large, messy human material can be transformed
into a structured, source-bound, inspectable memory substrate.

#### What Is Being Designed Beyond It

The next architectural layer is the runtime bridge between memory and behavior.

That layer activates the memory core the Ontology Machine creates.

It needs:

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

This bridge turns the semantic database from an archive into an active memory
system.

#### Ontology Layers As Retrieval Weights

Ontology layers are the bridge between stored meaning and dynamic behavior.

They can be interpreted as structured weighting surfaces over the memory core.
Each layer changes what the retrieval system considers important, how strongly a
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

Example:

```text
input: "Should I trust this new collaboration?"

active layers:
- relationship history
- trust and betrayal
- project continuity
- strategic risk
- value alignment

retrieval result:
- memories about similar collaborations
- evidence-bound outcomes
- recurring risk motifs
- stable value anchors

state shift:
- more cautious trust framing
- stronger source-checking tendency
- higher weight on prior collaboration patterns
- different response strategy
```

This is the important architectural step: ontology layers make memory
dynamically usable by turning stored semantic structure into retrieval weights
and state-shift parameters.

#### Ontology Lenses As State Parameters

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

A lens shapes which parts of the memory core are allowed to become active in a
given state.

This is how the same memory database can produce different state shifts under
different active frames.

Software-wise, a lens is a small retrieval and weighting program over the
corpus. It does not invent behavior. It decides which evidence, memories, and
semantic patterns should count for the current turn.

In simple terms:

```text
current input
-> active lens
-> query relevant taxonomy terms and ontology layers
-> retrieve source-bound memory packets
-> apply lens-specific weights
-> produce a compact state-shaping packet
-> inject that packet into the next model call
```

Each lens has a practical software role:

```text
continuity lens
  searches for recurring commitments, long-running projects, old decisions,
  promises, unresolved threads, and stable identity anchors.
  It increases the weight of memories that prevent the agent from contradicting
  its own history without reason.

moment lens
  searches for recent context, current task state, immediate constraints,
  open loops, and fresh signals.
  It increases the weight of what matters now, so the agent does not answer
  from abstract memory alone.

self-relation lens
  searches for self-descriptions, preferred working style, known limits,
  recurring doubts, strengths, and self-corrections.
  It shapes how the agent frames itself inside the answer.

direction lens
  searches for goals, unfinished movement, expected next steps, plans,
  trajectories, and prior turns where attention moved in a similar direction.
  It biases retrieval toward likely continuations instead of isolated facts.

stability lens
  searches for collapse points, friction, confusion, failure patterns,
  overload, and stabilizing routines.
  It raises the weight of memories that help keep a state coherent.

meaning lens
  searches for recurring interpretations, conceptual frames, metaphors,
  definitions, distinctions, and worldview-level claims.
  It shapes which interpretation of the current situation becomes dominant.

pressure lens
  searches for urgency, risk, threat, opportunity, cost, value conflict,
  emotional charge, and high-consequence patterns.
  It increases the weight of memories that should change priority or caution.

policy lens
  searches for learned rules, preferences, boundaries, decision principles,
  safety constraints, and action habits.
  It shapes what the agent should do, avoid, escalate, or ask before doing.
```

The important detail is that these lenses do not need to be mystical. They can
be implemented as ordinary software objects:

```json
{
  "lens_id": "pressure",
  "description": "Prioritizes costly, urgent, risky, or high-value context.",
  "taxonomy_terms": ["risk", "urgency", "conflict", "opportunity"],
  "ontology_layers": ["threat", "value_pressure", "decision_cost"],
  "query_surfaces": ["documents_fts", "evidence_atoms", "ontology_nodes"],
  "weights": {
    "recent": 0.8,
    "source_confidence": 1.0,
    "recurring_pattern": 1.2,
    "high_consequence": 1.5
  },
  "max_tokens": 600
}
```

At runtime, the lens returns a bounded packet:

```json
{
  "active_lens": "pressure",
  "state_effect": "increase caution and priority",
  "memory_packets": [
    {
      "claim": "Similar situations previously carried hidden coordination cost.",
      "evidence_refs": ["source:project-log:2026-01-14"],
      "weight": 0.87
    }
  ],
  "recommended_state_shift": {
    "caution": "+0.2",
    "priority": "+0.3",
    "ask_before_action": true
  }
}
```

The model does not need the whole corpus. It receives the small packet that the
lens compiled from the corpus. That packet is enough to shift the next answer
from generic response toward grounded continuity.

#### Personality Ground State

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

This lets a personality emerge from retrieval patterns instead of from a static
roleplay prompt.

#### Development Without Chaos

A dynamic psyche must be able to change without becoming incoherent.

That requires governance:

- source-bound evidence
- versioned semantic releases
- inspectable taxonomy changes
- explicit consolidation steps
- stable identity anchors
- bounded drift zones
- rollback through artifacts and releases
- read-only runtime access by default

The runtime produces traces. Those traces can later be reviewed, ingested, and
consolidated into the memory core.

This keeps development inspectable while still allowing the memory ground to
change over time.

#### End State

The end goal is a full dynamic psyche loop:

1. Build a persistent memory ground state from human material.
2. Expose it through taxonomy, ontology layers, and ontology lenses.
3. Retrieve context dynamically from that memory.
4. Use ontology-layer weights to shape the current agent state.
5. Record actions, decisions, conversations, and outcomes as traces.
6. Consolidate important traces back into the memory core.
7. Let the system develop over time without losing source grounding.

The result is a software architecture for persistent, inspectable,
evidence-bound agent continuity.

#### Short Public Framing

The Ontology Machine is the semantic memory engine for a larger architecture.

It builds the memory ground.

Future runtime layers can activate that ground through taxonomy-guided
retrieval, ontology-layer weighting, ontology lenses, salience weighting, and
consolidation.

Together, these components define a practical path toward dynamic digital
psyche systems: agents whose behavior is shaped by a persistent, structured,
evolving memory core whose ontology layers provide the retrieval weights needed
for dynamic state shifts.

#### On practicality, future AI model development and economic realities

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
