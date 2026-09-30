---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1205"
stix_relationship_id: "relationship--d74d9573-af4b-4984-ba5c-2cbd2b010fb2"
---
# Relationship 4932: G1048 — uses → T1205

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has used the TABLEFLIP traffic redirection utility to listen for specialized command packets on compromised FortiManager devices.(Citation: Mandiant Fortinet Zero Day)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d74d9573-af4b-4984-ba5c-2cbd2b010fb2`.
