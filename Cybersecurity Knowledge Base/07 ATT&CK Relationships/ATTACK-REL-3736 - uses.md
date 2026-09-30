---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1221"
target_object: "T1102"
stix_relationship_id: "relationship--bc7896a1-8be2-403b-b31d-b7d66104999d"
---
# Relationship 3736: S1221 — uses → T1102

**Source object:** [[01 ATT&CK/S1221 - MOPSLED|S1221: MOPSLED]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MOPSLED](https://attack.mitre.org/software/S1221) can use third-party web services such as GitHub and Google Drive for C2.(Citation: Google Cloud Mandiant UNC3886 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc7896a1-8be2-403b-b31d-b7d66104999d`.
