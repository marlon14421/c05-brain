---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1046"
target_object: "T1195"
stix_relationship_id: "relationship--08911cc4-20be-4499-8b19-f4c6151a7172"
---
# Relationship 0860: M1046 — mitigates → T1195

**Source object:** [[01 ATT&CK/M1046 - Boot Integrity|M1046: Boot Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1195 - Supply Chain Compromise|T1195: Supply Chain Compromise]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use secure methods to boot a system and verify the integrity of the operating system and loading mechanisms.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08911cc4-20be-4499-8b19-f4c6151a7172`.
