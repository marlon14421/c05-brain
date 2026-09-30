---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1248"
target_object: "T1071.001"
stix_relationship_id: "relationship--cf8967c7-1284-4484-b4bd-62ad0a6c5018"
---
# Relationship 3446: S1248 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1248 - XORIndex Loader|S1248: XORIndex Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[XORIndex Loader](https://attack.mitre.org/software/S1248) has used HTTPS POST to communicate with C2.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf8967c7-1284-4484-b4bd-62ad0a6c5018`.
