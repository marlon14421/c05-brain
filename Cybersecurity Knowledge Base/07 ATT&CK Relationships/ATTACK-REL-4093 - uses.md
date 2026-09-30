---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0513"
target_object: "T1027.003"
stix_relationship_id: "relationship--2e55a09d-0784-4a74-bd3a-6beca63adcce"
---
# Relationship 4093: S0513 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0513 - LiteDuke|S0513: LiteDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) has used image files to hide its loader component.(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e55a09d-0784-4a74-bd3a-6beca63adcce`.
