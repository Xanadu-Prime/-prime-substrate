1. Purpose
The naming layer establishes deterministic, unambiguous, and lineage‑preserving naming rules for all Prime‑era repositories.
Names are structural contracts — they define identity, inheritance, and operator intent.

2. Naming Principles
All names in the substrate follow four principles:

Clarity — the name must reveal purpose

Determinism — the name must not drift over time

Lineage — the name must reflect its position in the system

Non‑collision — no two artifacts may compete for the same semantic space

Naming is not cosmetic; it is governance.

3. Directory Naming Rules
Top‑level directories use numeric prefixes to enforce ordering and lineage:

Code
00_SUBSTRATE/
01_GOVERNANCE/
02_DOCTRINE/
03_PRIME_ERA/
99_META/
Rules:

prefix is two digits

underscore separates prefix from name

directory names are UPPER_SNAKE_CASE

prefixes define evaluation order and inheritance

To expand structural rules:
Open repo standards

4. File Naming Rules
Files follow kebab‑case with descriptive, declarative names:

Examples:

Code
substrate-spec.md
substrate-governance.md
operator-doctrine.md
dsr-1.md
Rules:

lowercase

hyphens separate words

no spaces

no overloaded terms

file names must reflect the artifact’s purpose

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

These terms may not be repurposed or redefined without Razor stabilization.

To deepen Razor mechanics:
Open razor principles

6. Lineage Naming Rules
Names must encode lineage:

parent → child relationships must be inferable

renames require DSR‑1 stabilization

lineage breaks must be declared explicitly

no silent name changes

To expand lineage rules:
Open lifecycle rules

7. Forbidden Patterns
The substrate prohibits:

camelCase

PascalCase

ambiguous abbreviations

overloaded names

names that imply behavior (e.g., manager, service, engine)

names that encode implementation details

The substrate is structural, not operational.

8. Naming Change Process
All naming changes must pass through:

Declaration

Scope Binding

Razor Stabilization

Propagation

This is DSR‑1 applied to naming.

To review DSR‑1:
Open DSR‑1

9. Out of Scope
Naming conventions do not define:

operator doctrine

runtime naming

scanner/vessel naming

TUI labels

Those belong to higher layers.

10. Change Log
v0.1 — Initial naming stub created for Prime‑era substrate governance.
