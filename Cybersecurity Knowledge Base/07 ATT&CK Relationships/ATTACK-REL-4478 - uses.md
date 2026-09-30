---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1017"
target_object: "T1059.010"
stix_relationship_id: "relationship--68f9103d-e772-493b-9ce6-fde4e2473207"
---
# Relationship 4478: S1017 — uses → T1059.010

**Source object:** [[01 ATT&CK/S1017 - OutSteel|S1017: OutSteel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.010 - AutoHotKey & AutoIT|T1059.010: AutoHotKey & AutoIT]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OutSteel](https://attack.mitre.org/software/S1017) was developed using the AutoIT scripting language.(Citation: Palo Alto Unit 42 OutSteel SaintBot February 2022 )

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68f9103d-e772-493b-9ce6-fde4e2473207`.
