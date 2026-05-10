1. Purpose
Repository standards define the structural, organizational, and inheritance rules that all Prime‑era repositories must follow.
These standards ensure consistency across the ecosystem and prevent structural drift.

2. Structural Requirements
All Prime‑era repositories must implement:

a deterministic directory hierarchy

numeric‑prefixed top‑level surfaces

declarative file naming

substrate‑aligned governance documents

a stable lineage model

To review naming rules:
Open naming conventions

3. Required Top‑Level Directories
Every Prime‑era repository must contain the following surfaces:

Code
00_SUBSTRATE/
01_GOVERNANCE/
02_DOCTRINE/
03_PRIME_ERA/
99_META/
Rules:

prefixes enforce evaluation order

surfaces may not be renamed without DSR‑1

new top‑level surfaces require Razor stabilization

To deepen substrate structure:
Open substrate spec

4. File Placement Rules
Files must be placed according to their semantic role:

substrate definitions → 00_SUBSTRATE/

governance rules → 01_GOVERNANCE/

operator doctrine → 02_DOCTRINE/

Prime‑era historical/logical documents → 03_PRIME_ERA/

metadata → 99_META/

No file may exist outside these surfaces without explicit stabilization.

5. Inheritance Model
All Prime‑era repositories inherit:

substrate invariants

naming conventions

governance rules

lifecycle mechanics

Inheritance is structural, not behavioral.
Repos may extend but not violate substrate rules.

To deepen lifecycle mechanics:
Open lifecycle rules

6. Required Documents
Each repository must include:

README.md — declarative overview

CHANGELOG.md — lineage record

VERSION — semantic version identifier

substrate‑aligned governance files

doctrine stubs (if applicable)

These documents form the repo’s operator interface.

7. Prohibited Structures
The substrate forbids:

ad‑hoc directories

ambiguous or duplicate surfaces

implementation‑specific naming

hidden state

undocumented lineage breaks

These patterns create drift and violate substrate determinism.

8. Modification Rules
Any structural change must pass through:

Declaration

Scope Binding

Razor Stabilization

Propagation

This is DSR‑1 applied to repository structure.

To review DSR‑1:
Open DSR‑1

9. Out of Scope
Repo standards do not define:

operator doctrine

runtime behavior

scanner or vessel logic

TUI surfaces

implementation details

These belong to higher layers.

10. Change Log
v0.1 — Initial repository standards stub created for Prime‑era substrate governance.
