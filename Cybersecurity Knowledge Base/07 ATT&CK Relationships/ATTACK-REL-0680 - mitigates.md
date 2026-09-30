---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1495"
stix_relationship_id: "relationship--b4dafcd2-fed8-4266-b83e-f4033ada0d55"
---
# Relationship 0680: M1026 — mitigates → T1495

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1495 - Firmware Corruption|T1495: Firmware Corruption]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent adversary access to privileged accounts or access necessary to replace system firmware.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b4dafcd2-fed8-4266-b83e-f4033ada0d55`.
