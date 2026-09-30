---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1046"
target_object: "T1553.006"
stix_relationship_id: "relationship--a1dda2bd-b47b-42b3-a7e5-dd58cfac1e15"
---
# Relationship 0492: M1046 — mitigates → T1553.006

**Source object:** [[01 ATT&CK/M1046 - Boot Integrity|M1046: Boot Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1553.006 - Code Signing Policy Modification|T1553.006: Code Signing Policy Modification]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use of Secure Boot may prevent some implementations of modification to code signing policies.(Citation: Microsoft TESTSIGNING Feb 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1dda2bd-b47b-42b3-a7e5-dd58cfac1e15`.
