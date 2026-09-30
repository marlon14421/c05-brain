---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0186"
target_object: "T1071.001"
stix_relationship_id: "relationship--d7bb00a0-fbe6-4622-84ed-be32ff5d8561"
---
# Relationship 4659: S0186 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0186 - DownPaper|S0186: DownPaper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DownPaper](https://attack.mitre.org/software/S0186) communicates to its C2 server over HTTP.(Citation: ClearSky Charming Kitten Dec 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7bb00a0-fbe6-4622-84ed-be32ff5d8561`.
