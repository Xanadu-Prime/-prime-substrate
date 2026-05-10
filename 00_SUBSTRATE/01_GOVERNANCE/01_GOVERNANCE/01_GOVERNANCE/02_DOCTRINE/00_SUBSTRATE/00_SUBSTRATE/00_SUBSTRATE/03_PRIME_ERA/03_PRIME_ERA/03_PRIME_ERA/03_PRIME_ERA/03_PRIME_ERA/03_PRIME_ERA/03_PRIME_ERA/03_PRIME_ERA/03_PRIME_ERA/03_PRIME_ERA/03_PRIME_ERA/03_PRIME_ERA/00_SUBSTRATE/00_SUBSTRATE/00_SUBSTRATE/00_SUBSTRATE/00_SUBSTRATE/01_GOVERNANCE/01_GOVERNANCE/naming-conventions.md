Prime‑Era Naming Conventions (v1.0)
1. Purpose
The naming layer defines the deterministic, unambiguous, and lineage‑preserving rules for naming all artifacts in the Prime substrate.
Names are structural contracts — they encode identity, intent, and position in the system.

Naming is not cosmetic.
Naming is governance.

To deepen naming governance:
Naming Governance Clause

2. Naming Principles
All names in the Prime substrate obey four principles:

Clarity — the name must reveal purpose

Determinism — the name must not drift over time

Lineage — the name must reflect its position in the system

Non‑collision — no two artifacts may compete for the same semantic space

If a name can be misread, overloaded, or reinterpreted, it violates the substrate.

To deepen lineage semantics:
Lifecycle Rules

3. Directory Naming Rules
Top‑level directories use numeric prefixes to enforce ordering and lineage:

Code
00_SUBSTRATE/
01_GOVERNANCE/
02_STRUCTURE/
03_PRIME_ERA/
99_META/
Rules:

prefix is two digits

underscore separates prefix from name

directory names are UPPER_SNAKE_CASE

prefixes define evaluation order and inheritance

directories may not be renamed without DSR‑1 stabilization

To deepen substrate topology:
Topology Map

4. File Naming Rules
Files follow kebab‑case with descriptive, declarative names:

Examples:

Code
substrate-spec.md
razor-principles.md
authorship-declaration.md
provenance-timeline.md
Rules:

lowercase

hyphens separate words

no spaces

no overloaded terms

file names must reflect the artifact’s purpose, not its implementation

To deepen file lineage:
Lineage Statement

5. Reserved Terms
The substrate reserves specific terms for canonical surfaces:

substrate

governance

doctrine

lifecycle

axioms

razor

prime-era

meta

lineage

naming

These terms may not be repurposed or redefined without Razor stabilization.

To deepen Razor mechanics:
Razor Principles

6. Lineage Naming Rules
Names must encode lineage:

parent → child relationships must be inferable

renames require DSR‑1 stabilization

lineage breaks must be explicitly declared

no silent name changes

successor epochs must use successor‑class names

To deepen successor naming:
Successor Naming Rules

7. Forbidden Patterns
The substrate prohibits:

camelCase

PascalCase

ambiguous abbreviations

overloaded names

names that imply behavior (e.g., manager, service, engine)

names that encode implementation details

names that drift over time

names that collapse multiple concepts into one

The substrate is structural, not operational.

8. Naming Change Process
All naming changes must pass through DSR‑1:

Declare — the Operator states the naming change

Scope‑Bind — assign the change to a region

Razor‑Stabilize — resolve contradictions

Propagate — update lineage and publish

No name may change outside this process.

To review DSR‑1:
DSR‑1

9. Naming Classes
Prime defines four naming classes:

1. Structural Names
Directories, schemas, invariants.
Must be stable across epochs.

2. Governance Names
Rules, principles, lifecycle surfaces.
Must reflect authority and scope.

3. Corpus Names
Prime‑era documents.
Must reflect lineage and purpose.

4. Public Names
External‑facing surfaces.
Must be clear, declarative, and non‑technical.

To deepen corpus structure:
Prime Corpus Index

10. Naming Invariants
The naming layer enforces:

no implicit names

no retroactive renames

no collisions

no ambiguous terms

no drift between layers

no names without declared purpose

Names are structural anchors.

11. Out of Scope
Naming conventions do not define:

runtime naming

scanner/vessel naming

operator doctrine

TUI labels

implementation identifiers

Those belong to higher layers.

12. Change Log
v1.0 — Naming conventions fully populated and stabilized for Prime governance.
