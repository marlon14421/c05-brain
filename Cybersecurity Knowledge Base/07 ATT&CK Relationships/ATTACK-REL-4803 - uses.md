---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1204.002"
stix_relationship_id: "relationship--21cd565f-4cdc-46d6-95b3-32b2d618674e"
---
# Relationship 4803: S0455 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) requires the user to double-click the executable to run the malicious HTA file or to download a malicious installer.(Citation: FireEye Metamorfo Apr 2018)(Citation: ESET Casbaneiro Oct 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21cd565f-4cdc-46d6-95b3-32b2d618674e`.
