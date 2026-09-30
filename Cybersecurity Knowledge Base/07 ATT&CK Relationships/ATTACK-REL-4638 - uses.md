---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0512"
target_object: "T1106"
stix_relationship_id: "relationship--67c21ae7-5dc3-4439-b5d1-df937abac3ad"
---
# Relationship 4638: S0512 — uses → T1106

**Source object:** [[01 ATT&CK/S0512 - FatDuke|S0512: FatDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FatDuke](https://attack.mitre.org/software/S0512) can call ShellExecuteW to open the default browser on the URL localhost.(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67c21ae7-5dc3-4439-b5d1-df937abac3ad`.
