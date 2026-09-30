---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1021"
target_object: "T1059.007"
stix_relationship_id: "relationship--b432bca9-8f75-431d-b0af-f43623e287d4"
---
# Relationship 0448: M1021 — mitigates → T1059.007

**Source object:** [[01 ATT&CK/M1021 - Restrict Web-Based Content|M1021: Restrict Web-Based Content]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Script blocking extensions can help prevent the execution of JavaScript and HTA files that may commonly be used during the exploitation process. For malicious code served up through ads, adblockers can help prevent that code from executing in the first place.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b432bca9-8f75-431d-b0af-f43623e287d4`.
