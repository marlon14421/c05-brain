---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0512"
target_object: "T1082"
stix_relationship_id: "relationship--4f5fd1ed-a91e-4a9e-b2e8-6c45cc31e065"
---
# Relationship 7866: S0512 — uses → T1082

**Source object:** [[01 ATT&CK/S0512 - FatDuke|S0512: FatDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FatDuke](https://attack.mitre.org/software/S0512) can collect the user name, Windows version, computer name, and available space on discs from a compromised host.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f5fd1ed-a91e-4a9e-b2e8-6c45cc31e065`.
