---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1197"
stix_relationship_id: "relationship--4b4d8f9e-a416-4af6-9c20-582892601668"
---
# Relationship 0491: M1037 — mitigates → T1197

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1197 - BITS Jobs|T1197: BITS Jobs]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Modify network and/or host firewall rules, as well as other network controls, to only allow legitimate BITS traffic.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b4d8f9e-a416-4af6-9c20-582892601668`.
