---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0093"
target_object: "T1105"
stix_relationship_id: "relationship--984a898c-f469-4e7c-94c6-bf512ec69938"
---
# Relationship 3505: S0093 — uses → T1105

**Source object:** [[01 ATT&CK/S0093 - Backdoor.Oldrea|S0093: Backdoor.Oldrea]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Backdoor.Oldrea](https://attack.mitre.org/software/S0093) can download additional modules from C2.(Citation: Gigamon Berserk Bear October 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--984a898c-f469-4e7c-94c6-bf512ec69938`.
