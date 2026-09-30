---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1187"
target_object: "T1071.001"
stix_relationship_id: "relationship--85fbeb33-0d9f-45a2-a454-1f77e51b0c4d"
---
# Relationship 3196: S1187 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1187 - reGeorg|S1187: reGeorg]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[reGeorg](https://attack.mitre.org/software/S1187) can use HTTP to tunnel connections in and out of targeted networks.(Citation: Fortinet reGeorg MAR 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85fbeb33-0d9f-45a2-a454-1f77e51b0c4d`.
