1. Purpose
Lifecycle rules define the temporal mechanics of the substrate:
how decisions enter, stabilize, propagate, persist, and dissolve.

The lifecycle ensures that all changes are time‑safe, deterministic, and operator‑controlled.

2. Lifecycle Principles
All lifecycle behavior follows four principles:

Temporal determinism — no ambiguous transitions

Stability before propagation — nothing moves forward until contradictions are resolved

Lineage continuity — every state must be traceable

Operator primacy — the operator defines when a lifecycle phase begins or ends

Lifecycle is the substrate’s time geometry.

3. Canonical Lifecycle Phases
Every change in the substrate passes through four phases:

Instantiation — the change is declared

Activation — the change becomes eligible for stabilization

Operation — the change performs its functional role

Resolution — the change completes, persists, or dissolves

To deepen these phases:
Open lifecycle semantics

4. Phase Rules
4.1 Instantiation
A change enters the system only when explicitly declared.
Implicit or inferred changes are forbidden.

To expand instantiation:
Define instantiation phase

4.2 Activation
A change becomes eligible for stabilization only when:

scope is bound

affected surfaces are known

lineage is intact

no hidden dependencies exist

To deepen activation:
Define activation phase

4.3 Operation
A change is considered “active” when:

it has passed Razor stabilization

it has a contradiction‑free form

it is ready to interact with the substrate

To expand operation:
Define operation phase

4.4 Resolution
A change completes when:

final state is emitted

lineage is updated

the change either persists or dissolves

no unresolved contradictions remain

To deepen resolution:
Define resolution phase

5. Lifecycle Enforcement
Lifecycle transitions are enforced through:

DSR‑1 — declaration, scope binding, Razor stabilization

lineage checks

structural invariants

operator review

No phase may be skipped.
No transition may occur implicitly.

To review DSR‑1:
Open DSR‑1

6. Invalid Transitions
The substrate forbids:

activation without declaration

operation without stabilization

resolution without lineage update

propagation without Razor approval

silent rollback or mutation

Invalid transitions must be rejected or escalated.

7. Propagation Rules
Propagation occurs only when:

the change is fully stabilized

lineage is updated

no contradictions remain

the operator authorizes propagation

Propagation is the final act of lifecycle completion.

8. Dissolution Rules
A change may dissolve only when:

it has no active dependents

lineage can be cleanly reversed

the operator explicitly authorizes dissolution

Dissolution is a first‑class lifecycle event, not an error.

9. Out of Scope
Lifecycle rules do not define:

runtime behavior

operator doctrine

scanner/vessel execution semantics

TUI interactions

These belong to higher layers.

10. Change Log
v0.1 — Initial lifecycle rules stub created for Prime‑era substrate governance.
