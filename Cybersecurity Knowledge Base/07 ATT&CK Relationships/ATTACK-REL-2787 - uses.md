---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0026"
target_object: "T1005"
stix_relationship_id: "relationship--ff746d3d-2ebe-46e9-87f6-5ddd8abbfda3"
---
# Relationship 2787: C0026 — uses → T1005

**Source object:** [[01 ATT&CK/C0026 - C0026|C0026: C0026]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0026](https://attack.mitre.org/campaigns/C0026), the threat actors collected documents from compromised hosts.(Citation: Mandiant Suspected Turla Campaign February 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff746d3d-2ebe-46e9-87f6-5ddd8abbfda3`.
