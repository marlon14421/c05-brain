---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0531"
target_object: "T1102.002"
stix_relationship_id: "relationship--30e68a86-bbfc-4677-9815-b256be560f09"
---
# Relationship 2869: S0531 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0531 - Grandoreiro|S0531: Grandoreiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Grandoreiro](https://attack.mitre.org/software/S0531) can utilize web services including Google sites to send and receive C2 data.(Citation: IBM Grandoreiro April 2020)(Citation: ESET Grandoreiro April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30e68a86-bbfc-4677-9815-b256be560f09`.
