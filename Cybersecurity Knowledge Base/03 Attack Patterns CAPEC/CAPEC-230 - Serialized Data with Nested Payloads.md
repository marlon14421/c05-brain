---
type: "Attack Pattern"
source: "MITRE CAPEC"
id: "CAPEC-230"
status: "Draft"
---
# CAPEC-230: Serialized Data with Nested Payloads

**Abstraction:** Standard  
**Catalog severity:** High  
**Catalog likelihood:** Medium

## Description

Applications often need to transform data in and out of a data format (e.g., XML and YAML) by using a parser. It may be possible for an adversary to inject data that may have an adverse effect on the parser when it is being processed. Many data format languages allow the definition of macro-like structures that can be used to simplify the creation of complex structures. By nesting these structures, causing the data to be repeatedly substituted, an adversary can cause the parser to consume more resources while processing, causing excessive memory consumption and CPU utilization.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

## Source

- [CAPEC-230 on capec.mitre.org](https://capec.mitre.org/data/definitions/230.html)
- Dataset: [MITRE CAPEC catalog](https://capec.mitre.org/data/downloads.html), version 3.9 (retrieved 2026-09-30).
