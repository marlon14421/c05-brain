---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1078.002"
stix_relationship_id: "relationship--b7a9afc1-3bbf-4eda-9709-5392156c1e41"
---
# Relationship 3125: G0092 — uses → T1078.002

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has used stolen domain admin accounts to compromise additional hosts.(Citation: IBM TA505 April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7a9afc1-3bbf-4eda-9709-5392156c1e41`.
