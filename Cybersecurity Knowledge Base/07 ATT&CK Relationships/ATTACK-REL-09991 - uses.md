---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0468"
target_object: "T1098.004"
stix_relationship_id: "relationship--13d595d2-9497-4bbe-be74-6e2a3a4dde06"
---
# Relationship 9991: S0468 — uses → T1098.004

**Source object:** [[01 ATT&CK/S0468 - Skidmap|S0468: Skidmap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1098.004 - SSH Authorized Keys|T1098.004: SSH Authorized Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Skidmap](https://attack.mitre.org/software/S0468) has the ability to add the public key of its handlers to the authorized_keys file to maintain persistence on an infected host.(Citation: Trend Micro Skidmap)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13d595d2-9497-4bbe-be74-6e2a3a4dde06`.
