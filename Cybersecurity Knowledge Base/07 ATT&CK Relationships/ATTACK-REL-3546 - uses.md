---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1219"
target_object: "T1095"
stix_relationship_id: "relationship--b80f4569-d64a-48d4-9ff1-a4e4768e000c"
---
# Relationship 3546: S1219 — uses → T1095

**Source object:** [[01 ATT&CK/S1219 - REPTILE|S1219: REPTILE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[REPTILE](https://attack.mitre.org/software/S1219) can communicate using TLS over raw TCP.(Citation: Google Cloud Mandiant UNC3886 2024)(Citation: Mandiant Fortinet Zero Day)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b80f4569-d64a-48d4-9ff1-a4e4768e000c`.
