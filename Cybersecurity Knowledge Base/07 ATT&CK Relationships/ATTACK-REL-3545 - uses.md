---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0391"
target_object: "T1033"
stix_relationship_id: "relationship--6337062d-04c1-43df-a72b-8719a31102a0"
---
# Relationship 3545: S0391 — uses → T1033

**Source object:** [[01 ATT&CK/S0391 - HAWKBALL|S0391: HAWKBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HAWKBALL](https://attack.mitre.org/software/S0391) can collect the user name of the system.(Citation: FireEye HAWKBALL Jun 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6337062d-04c1-43df-a72b-8719a31102a0`.
