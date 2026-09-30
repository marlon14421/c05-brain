---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0180"
target_object: "T1049"
stix_relationship_id: "relationship--ed561ab1-db94-4dbe-873b-d3e6cb488c4d"
---
# Relationship 3560: S0180 — uses → T1049

**Source object:** [[01 ATT&CK/S0180 - Volgmer|S0180: Volgmer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Volgmer](https://attack.mitre.org/software/S0180) can gather information about TCP connection state.(Citation: Symantec Volgmer Aug 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed561ab1-db94-4dbe-873b-d3e6cb488c4d`.
