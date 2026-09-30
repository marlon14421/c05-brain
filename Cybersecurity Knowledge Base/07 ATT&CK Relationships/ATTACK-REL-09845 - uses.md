---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0622"
target_object: "T1134"
stix_relationship_id: "relationship--57aa85a9-8484-4a1a-947f-3d266d2b3c7d"
---
# Relationship 9845: S0622 — uses → T1134

**Source object:** [[01 ATT&CK/S0622 - AppleSeed|S0622: AppleSeed]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134 - Access Token Manipulation|T1134: Access Token Manipulation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleSeed](https://attack.mitre.org/software/S0622) can gain system level privilege by passing SeDebugPrivilege to the AdjustTokenPrivilege API.(Citation: Malwarebytes Kimsuky June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57aa85a9-8484-4a1a-947f-3d266d2b3c7d`.
