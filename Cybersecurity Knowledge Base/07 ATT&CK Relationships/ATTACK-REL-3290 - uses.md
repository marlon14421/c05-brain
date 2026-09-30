---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0554"
target_object: "T1105"
stix_relationship_id: "relationship--87182fef-ddbc-466e-b55b-989f10592d0c"
---
# Relationship 3290: S0554 — uses → T1105

**Source object:** [[01 ATT&CK/S0554 - Egregor|S0554: Egregor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Egregor](https://attack.mitre.org/software/S0554) has the ability to download files from its C2 server.(Citation: Cybereason Egregor Nov 2020)(Citation: Intrinsec Egregor Nov 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87182fef-ddbc-466e-b55b-989f10592d0c`.
