---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0443"
target_object: "T1049"
stix_relationship_id: "relationship--b565458d-7831-4010-9596-4d6fe44fd738"
---
# Relationship 3042: S0443 — uses → T1049

**Source object:** [[01 ATT&CK/S0443 - MESSAGETAP|S0443: MESSAGETAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

After loading the keyword and phone data files, [MESSAGETAP](https://attack.mitre.org/software/S0443) begins monitoring all network connections to and from the victim server. (Citation: FireEye MESSAGETAP October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b565458d-7831-4010-9596-4d6fe44fd738`.
