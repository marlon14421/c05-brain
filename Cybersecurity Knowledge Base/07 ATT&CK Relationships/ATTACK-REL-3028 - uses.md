---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0017"
target_object: "T1033"
stix_relationship_id: "relationship--ec037573-058a-43d5-a76e-bd76e99953dd"
---
# Relationship 3028: S0017 — uses → T1033

**Source object:** [[01 ATT&CK/S0017 - BISCUIT|S0017: BISCUIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BISCUIT](https://attack.mitre.org/software/S0017) has a command to gather the username from the system.(Citation: Mandiant APT1 Appendix)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec037573-058a-43d5-a76e-bd76e99953dd`.
