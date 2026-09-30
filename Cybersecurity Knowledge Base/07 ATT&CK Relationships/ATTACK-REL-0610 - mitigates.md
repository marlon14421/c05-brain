---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1557"
stix_relationship_id: "relationship--3e3c926e-4f21-40f0-b869-6b3c0e35e243"
---
# Relationship 0610: M1042 — mitigates → T1557

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557 - Adversary-in-the-Middle|T1557: Adversary-in-the-Middle]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disable legacy network protocols that may be used to intercept network traffic if applicable, especially those that are not needed within an environment.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e3c926e-4f21-40f0-b869-6b3c0e35e243`.
