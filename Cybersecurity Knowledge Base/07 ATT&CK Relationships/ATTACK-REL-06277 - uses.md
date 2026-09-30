---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0203"
target_object: "T1007"
stix_relationship_id: "relationship--935f8b6e-cd74-46c4-9a74-f763b4f13955"
---
# Relationship 6277: S0203 — uses → T1007

**Source object:** [[01 ATT&CK/S0203 - Hydraq|S0203: Hydraq]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hydraq](https://attack.mitre.org/software/S0203) creates a backdoor through which remote attackers can monitor services.(Citation: Symantec Trojan.Hydraq Jan 2010)(Citation: Symantec Hydraq Jan 2010)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--935f8b6e-cd74-46c4-9a74-f763b4f13955`.
