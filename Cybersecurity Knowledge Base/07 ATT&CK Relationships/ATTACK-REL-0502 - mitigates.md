---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1046"
target_object: "T1495"
stix_relationship_id: "relationship--f365854f-76e6-4746-bab8-2f2b94b50087"
---
# Relationship 0502: M1046 — mitigates → T1495

**Source object:** [[01 ATT&CK/M1046 - Boot Integrity|M1046: Boot Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1495 - Firmware Corruption|T1495: Firmware Corruption]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Check the integrity of the existing BIOS and device firmware to determine if it is vulnerable to modification.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f365854f-76e6-4746-bab8-2f2b94b50087`.
