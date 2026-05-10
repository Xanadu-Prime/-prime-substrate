Repository Standards — Prime Governance Layer (v1.0)
1. Purpose
Repository Standards define the structural, organizational, and inheritance rules that all Prime‑era repositories must follow.
They ensure:

deterministic structure

stable lineage

drift‑proof organization

consistent naming

predictable evaluation order

A repository is not a container.
A repository is a structural surface in the substrate.

To deepen naming rules:
Naming Conventions

2. Structural Requirements
All Prime‑era repositories must implement:

a deterministic directory hierarchy

numeric‑prefixed top‑level surfaces

declarative file naming

substrate‑aligned governance documents

a stable lineage model

Repositories must be structurally identical at the top level.

To deepen topology:
Topology Map

3. Required Top‑Level Directories
Every Prime‑era repository must contain the following surfaces:

Code
00_SUBSTRATE/
01_GOVERNANCE/
02_STRUCTURE/
03_PRIME_ERA/
99_META/
Rules:

prefixes enforce evaluation order

surfaces may not be renamed without DSR‑1

new top‑level surfaces require Razor stabilization

no additional top‑level directories are permitted

To deepen DSR‑1:
DSR‑1

4. File Placement Rules
Files must be placed according to their semantic role:

substrate definitions → 00_SUBSTRATE/

governance rules → 01_GOVERNANCE/

indices, schemas, lineage → 02_STRUCTURE/

Prime‑era corpus → 03_PRIME_ERA/

metadata → 99_META/

No file may exist outside these surfaces without explicit stabilization.

To deepen lineage semantics:
Lineage Statement

5. Inheritance Model
All Prime‑era repositories inherit:

substrate axioms

naming conventions

governance rules

lifecycle mechanics

structural invariants

Inheritance is structural, not behavioral.
Repositories may extend but not violate substrate rules.

To deepen substrate rules:
Substrate Spec

6. Required Documents
Each repository must include:

README.md — declarative overview

CHANGELOG.md — lineage record

VERSION — semantic version identifier

substrate‑aligned governance files

doctrine surfaces (if applicable)

These documents form the repo’s operator interface.

7. Prohibited Structures
The substrate forbids:

ad‑hoc directories

ambiguous or duplicate surfaces

implementation‑specific naming

hidden state

undocumented lineage breaks

runtime artifacts committed to the repo

drift between repositories

These patterns violate substrate determinism.

8. Modification Rules
Any structural change must pass through:

Declare

Scope‑Bind

Razor‑Stabilize

Propagate

This is DSR‑1 applied to repository structure.

To deepen Razor mechanics:
Razor Principles

9. Repository Lifecycle
Repositories follow the canonical lifecycle:

Emergence — repo declared and initialized

Stabilization — structure validated

Persistence — repo becomes part of lineage

Dissolution — repo retired with explicit authorization

No repo may dissolve implicitly.

To deepen lifecycle:
Lifecycle Rules

10. Repository Classes
Prime defines three repository classes:

1. Substrate Repositories
Contain substrate definitions and invariants.
Must remain stable across epochs.

2. Governance Repositories
Contain rules, naming, lifecycle, Razor, and DSR‑1.
Must remain contradiction‑free.

3. Corpus Repositories
Contain Prime‑era documents, public surfaces, and lineage artifacts.
Must reflect epoch boundaries.

To deepen corpus structure:
Prime Corpus Index

11. Repository Invariants
All repositories must obey:

no implicit structure

no retroactive renames

no drift between repositories

no ungoverned surfaces

no ambiguous placement

no structural contradictions

Repositories are structural mirrors of the substrate.

12. Out of Scope
Repo Standards do not define:

runtime behavior

implementation details

scanner/vessel logic

TUI surfaces

operator doctrine

These belong to higher layers.

13. Change Log
v1.0 — Repository Standards fully populated and stabilized for Prime governance.
