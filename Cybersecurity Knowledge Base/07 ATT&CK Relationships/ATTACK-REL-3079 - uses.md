---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0180"
target_object: "T1007"
stix_relationship_id: "relationship--6139509a-709b-4ef4-81fb-25b9a35e2c60"
---
# Relationship 3079: S0180 — uses → T1007

**Source object:** [[01 ATT&CK/S0180 - Volgmer|S0180: Volgmer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Volgmer](https://attack.mitre.org/software/S0180) queries the system to identify existing services.(Citation: US-CERT Volgmer Nov 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6139509a-709b-4ef4-81fb-25b9a35e2c60`.
