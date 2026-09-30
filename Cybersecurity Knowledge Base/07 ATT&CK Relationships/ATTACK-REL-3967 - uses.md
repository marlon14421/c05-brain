---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1026"
target_object: "T1566.001"
stix_relationship_id: "relationship--92c83d10-7e4f-4d4a-9766-b2162ee72cb1"
---
# Relationship 3967: G1026 — uses → T1566.001

**Source object:** [[01 ATT&CK/G1026 - Malteiro|G1026: Malteiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Malteiro](https://attack.mitre.org/groups/G1026) has sent spearphishing emails containing malicious .zip files.(Citation: SCILabs Malteiro 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92c83d10-7e4f-4d4a-9766-b2162ee72cb1`.
