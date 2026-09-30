---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1548.003"
stix_relationship_id: "relationship--b69490a4-3768-405e-856d-da11d95183e7"
---
# Relationship 1211: M1028 — mitigates → T1548.003

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1548.003 - Sudo and Sudo Caching|T1548.003: Sudo and Sudo Caching]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensuring that the tty_tickets setting is enabled will prevent this leakage across tty sessions.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b69490a4-3768-405e-856d-da11d95183e7`.
