---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1204.005"
stix_relationship_id: "relationship--97d77f42-8b8e-48e1-b772-b6cb5c435249"
---
# Relationship 0675: M1017 — mitigates → T1204.005

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1204.005 - Malicious Library|T1204.005: Malicious Library]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Train developers to be aware of the existence of malicious libraries and how to avoid installing them.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97d77f42-8b8e-48e1-b772-b6cb5c435249`.
