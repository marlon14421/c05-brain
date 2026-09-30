---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0345"
target_object: "T1070.004"
stix_relationship_id: "relationship--acdc53fa-91d6-4417-bc7b-83c220ec9fae"
---
# Relationship 2980: S0345 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0345 - Seasalt|S0345: Seasalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Seasalt](https://attack.mitre.org/software/S0345) has a command to delete a specified file.(Citation: Mandiant APT1 Appendix)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--acdc53fa-91d6-4417-bc7b-83c220ec9fae`.
