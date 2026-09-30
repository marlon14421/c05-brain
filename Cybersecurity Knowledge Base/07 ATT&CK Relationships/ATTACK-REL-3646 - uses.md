---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1156"
target_object: "T1041"
stix_relationship_id: "relationship--56b308f6-0ec9-42cd-8fc7-147c8ecd5c40"
---
# Relationship 3646: S1156 — uses → T1041

**Source object:** [[01 ATT&CK/S1156 - Manjusaka|S1156: Manjusaka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Manjusaka](https://attack.mitre.org/software/S1156) data exfiltration takes place over HTTP channels.(Citation: Talos Manjusaka 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56b308f6-0ec9-42cd-8fc7-147c8ecd5c40`.
