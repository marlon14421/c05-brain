---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1041"
stix_relationship_id: "relationship--520f5440-740f-4efe-850e-ea4db340aef1"
---
# Relationship 3273: G0032 — uses → T1041

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has exfiltrated data and files over a C2 channel through its various tools and malware.(Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster Loaders)(Citation: McAfee Lazarus Resurfaces Feb 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--520f5440-740f-4efe-850e-ea4db340aef1`.
