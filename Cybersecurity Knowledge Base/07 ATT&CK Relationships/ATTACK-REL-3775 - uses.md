---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1105"
stix_relationship_id: "relationship--1525d82a-05a7-4027-9d2d-02f8039d68b5"
---
# Relationship 3775: G0004 — uses → T1105

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) has used tools to download files to compromised machines.(Citation: Microsoft NICKEL December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1525d82a-05a7-4027-9d2d-02f8039d68b5`.
