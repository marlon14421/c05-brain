---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1113"
stix_relationship_id: "relationship--11010986-1b4d-4158-b47d-bbff34306c98"
---
# Relationship 3428: S0128 — uses → T1113

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BADNEWS](https://attack.mitre.org/software/S0128) has a command to take a screenshot and send it to the C2 server.(Citation: Forcepoint Monsoon)(Citation: PaloAlto Patchwork Mar 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11010986-1b4d-4158-b47d-bbff34306c98`.
