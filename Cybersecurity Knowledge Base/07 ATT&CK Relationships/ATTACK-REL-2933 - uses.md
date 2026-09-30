---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0514"
target_object: "T1132.001"
stix_relationship_id: "relationship--86dddc68-9032-4467-be3c-a48d3bacfd06"
---
# Relationship 2933: S0514 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0514 - WellMess|S0514: WellMess]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[WellMess](https://attack.mitre.org/software/S0514) has used Base64 encoding to uniquely identify communication to and from the C2.(Citation: CISA WellMess July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86dddc68-9032-4467-be3c-a48d3bacfd06`.
