---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0084"
target_object: "T1095"
stix_relationship_id: "relationship--cef7d272-ee0c-4379-9d7b-63adf1f40252"
---
# Relationship 4614: S0084 — uses → T1095

**Source object:** [[01 ATT&CK/S0084 - Mis-Type|S0084: Mis-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mis-Type](https://attack.mitre.org/software/S0084) network traffic can communicate over a raw socket.(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cef7d272-ee0c-4379-9d7b-63adf1f40252`.
