---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0649"
target_object: "T1112"
stix_relationship_id: "relationship--331f7990-d817-49ec-9d55-c4c64da7f4a6"
---
# Relationship 3268: S0649 — uses → T1112

**Source object:** [[01 ATT&CK/S0649 - SMOKEDHAM|S0649: SMOKEDHAM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SMOKEDHAM](https://attack.mitre.org/software/S0649) has modified registry keys for persistence, to enable credential caching for credential access, and to facilitate lateral movement via RDP.(Citation: FireEye SMOKEDHAM June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--331f7990-d817-49ec-9d55-c4c64da7f4a6`.
