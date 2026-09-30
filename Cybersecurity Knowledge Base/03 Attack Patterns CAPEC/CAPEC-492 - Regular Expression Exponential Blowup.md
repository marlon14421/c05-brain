---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-492"
status: "Draft"
---
# CAPEC-492: Regular Expression Exponential Blowup

**Abstraction:** Standard  
**Catalog severity:** Not stated  
**Catalog likelihood:** Not stated

## Description

An adversary may execute an attack on a program that uses a poor Regular Expression(Regex) implementation by choosing input that results in an extreme situation for the Regex. A typical extreme situation operates at exponential time compared to the input size. This is due to most implementations using a Nondeterministic Finite Automaton(NFA) state machine to be built by the Regex algorithm since NFA allows backtracking and thus more complex regular expressions.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-492 on capec.mitre.org](https://capec.mitre.org/data/definitions/492.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
