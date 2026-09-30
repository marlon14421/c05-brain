---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1051"
target_object: "T1602.002"
stix_relationship_id: "relationship--ae8a7787-7915-4dfa-bf79-73fd76dc6473"
---
# Relationship 0929: M1051 — mitigates → T1602.002

**Source object:** [[01 ATT&CK/M1051 - Update Software|M1051: Update Software]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1602.002 - Network Device Configuration Dump|T1602.002: Network Device Configuration Dump]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Keep system images and software updated and migrate to SNMPv3.(Citation: Cisco Blog Legacy Device Attacks)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae8a7787-7915-4dfa-bf79-73fd76dc6473`.
