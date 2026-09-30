---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1098.004"
stix_relationship_id: "relationship--d6e1026a-a33e-46a3-832e-ff9b36d52c07"
---
# Relationship 7504: G0139 — uses → T1098.004

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has added RSA keys in authorized_keys .(Citation: Aqua TeamTNT August 2020)(Citation: Cisco Talos Intelligence Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6e1026a-a33e-46a3-832e-ff9b36d52c07`.
