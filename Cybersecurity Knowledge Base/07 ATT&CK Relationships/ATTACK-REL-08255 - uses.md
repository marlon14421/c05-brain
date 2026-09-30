---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1484.001"
stix_relationship_id: "relationship--522d72b0-e8ff-43d9-bd2d-911f7b5c89a4"
---
# Relationship 8255: G0096 — uses → T1484.001

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1484.001 - Group Policy Modification|T1484.001: Group Policy Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used scheduled tasks created via Group Policy Objects (GPOs) to deploy ransomware.(Citation: apt41_mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--522d72b0-e8ff-43d9-bd2d-911f7b5c89a4`.
