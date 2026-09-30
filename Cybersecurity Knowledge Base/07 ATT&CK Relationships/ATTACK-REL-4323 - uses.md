---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0385"
target_object: "T1125"
stix_relationship_id: "relationship--30be2552-9794-4eef-b3b6-fa663f68784b"
---
# Relationship 4323: S0385 — uses → T1125

**Source object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[njRAT](https://attack.mitre.org/software/S0385) can access the victim's webcam.(Citation: Fidelis njRAT June 2013)(Citation: Citizen Lab Group5)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30be2552-9794-4eef-b3b6-fa663f68784b`.
