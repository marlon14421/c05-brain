---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1032"
target_object: "T1021.004"
stix_relationship_id: "relationship--77c5bb7d-9584-4d57-850b-6349984181a8"
---
# Relationship 1051: M1032 — mitigates → T1021.004

**Source object:** [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032: Multi-factor Authentication]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.004 - SSH|T1021.004: SSH]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Require multi-factor authentication for SSH connections wherever possible, such as password protected SSH keys.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77c5bb7d-9584-4d57-850b-6349984181a8`.
