# TIG Operators

**Status: Exploratory. Emerged from simulations, not derived from theory.**

See [EXPLORATORY.md](EXPLORATORY.md) for context on how these artifacts should be treated.

---

## Overview

During simulation, we needed a vocabulary for discrete actions nodes could take. These 10 operators (0-9) plus the meta-operator (Ω̂) emerged as useful primitives.

They are **not** proven to be:
- Minimal (maybe fewer would suffice)
- Complete (maybe more are needed)
- Universal (maybe different systems need different primitives)

They're what worked in our toy sim. Included for completeness.

---

## Base Operators (0-9)

### 0 — Void

**Symbol**: ∅  
**Action**: Null state, initialization, emptiness

The ground state. Return to zero. Clear the slate.

In compute: cold start, memory wipe, factory reset.

---

### 1 — Lattice

**Symbol**: ⊞  
**Action**: Structure formation, create order

Build a scaffold. Establish positions. Form the geometry.

In compute: cluster topology setup, index construction, schema creation.

**Inverse**: Chaos (6)

---

### 2 — Counter

**Symbol**: #  
**Action**: Measure, increment, enumerate

Count what exists. Track occurrences. Discrete observation.

In compute: metrics collection, reference counting, sequence numbers.

---

### 3 — Progress

**Symbol**: →  
**Action**: Move forward, advance, evolve

Time's arrow. State A to state B. Growth.

In compute: job execution, pipeline stages, version upgrades.

**Note**: Progress may be irreversible.

---

### 4 — Collapse

**Symbol**: ↓  
**Action**: Reduce options to one, decide, commit

Many possibilities become one actuality. The measurement problem.

In compute: load balancer selection, consensus finalization, query aggregation.

**Note**: Information is lost in collapse.

---

### 5 — Balance

**Symbol**: ⚖  
**Action**: Seek equilibrium, redistribute, equalize

Find the stable middle. Counteract imbalance. Homeostasis.

In compute: load balancing, resource allocation, rate limiting.

**Property**: Idempotent (Balance → Balance = Balance)

---

### 6 — Chaos

**Symbol**: ☆  
**Action**: Inject entropy, randomize, disrupt

Break existing structure. Introduce uncertainty. Prevent stagnation.

In compute: chaos engineering, fuzzing, shuffle operations.

**Inverse**: Lattice (1)

---

### 7 — Harmony

**Symbol**: ♪  
**Action**: Align, synchronize, resonate

Bring disparate elements into phase. Coherent oscillation.

In compute: clock sync, replica convergence, cache coherence.

---

### 8 — Breath

**Symbol**: ∿  
**Action**: Oscillate, cycle, pulse

Inhale/exhale. Periodic expansion and contraction. Rhythm.

In compute: GC cycles, batch windows, health check intervals, autoscaling.

---

### 9 — Reset

**Symbol**: ↺  
**Action**: Return to known state, restart

Different from Void: Reset returns to *defined* initial state, not emptiness.

In compute: reboot, rollback, circuit breaker reset.

**Property**: Idempotent (Reset → Reset = Reset)

---

## The Ω̂ Operator (Omega-Hat)

**Symbol**: Ω̂  
**Name**: Unification / Coherence Keeper  
**Action**: Meta-operation, orchestration

Ω̂ is not one action — it's the operator that chooses which operators to apply.

### Function

1. **Observe**: Monitor S* across the system
2. **Decide**: Which operator(s) would restore coherence?
3. **Apply**: Execute the chosen sequence
4. **Verify**: Did S* improve?

### In Trinity Terms

Ω̂ is the macro's awareness of its micros. It's the cluster knowing its nodes. The self holding its trinity together.

### Example Logic
```
if S* dropping from imbalance:
    apply Balance (5)
    
if S* dropping from accumulated errors:
    apply Reset (9)
    
if S* stable but stagnant:
    apply Chaos (6) then Progress (3)
```

---

## Operator Composition

Operators can be sequenced:

**Reset-Lattice-Progress** (recovery):
```
9 → 1 → 3
Return to known state, rebuild structure, move forward
```

**Chaos-Balance-Harmony** (resilience test):
```
6 → 5 → 7
Inject disorder, rebalance, verify alignment
```

---

## Operator Properties

### Inverses (approximate)

- Lattice (1) ↔ Chaos (6)
- Progress (3) ↔ Reset (9) — partial, information may be lost

### Idempotent

- Balance (5): Balancing a balanced system changes nothing
- Reset (9): Resetting from initial state changes nothing

### Non-commutative

Most operators don't commute:
```
Progress → Collapse ≠ Collapse → Progress
```

Order matters.

---

## Open Questions

1. **Completeness**: Can all coherence-maintaining actions be expressed with these?
2. **Minimality**: Are any operators derivable from others?
3. **Universality**: Do different domains need different operator sets?
4. **Algebra**: Is there a group structure? What are the symmetries?

---

## Honest Assessment

These operators are a naming convention that was useful in our simulations. They might map to something fundamental — least action paths, geometric transformations, categorical morphisms.

Or they might just be convenient labels.

We don't know yet.

---

*"Every action is one of these, or a composition of them. Maybe."*
