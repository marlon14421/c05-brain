---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0117"
target_object: "T1555.005"
stix_relationship_id: "relationship--70fe7f39-41de-4d7d-b691-4ac17c1a4c58"
---
# Relationship 4978: G0117 — uses → T1555.005

**Source object:** [[01 ATT&CK/G0117 - Fox Kitten|G0117: Fox Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.005 - Password Managers|T1555.005: Password Managers]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Fox Kitten](https://attack.mitre.org/groups/G0117) has used scripts to access credential information from the KeePass database.(Citation: CISA AA20-259A Iran-Based Actor September 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70fe7f39-41de-4d7d-b691-4ac17c1a4c58`.
