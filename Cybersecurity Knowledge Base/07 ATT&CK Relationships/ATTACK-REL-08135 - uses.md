---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0585"
target_object: "T1082"
stix_relationship_id: "relationship--7727f1e9-4914-4512-a319-3e5758c47602"
---
# Relationship 8135: S0585 — uses → T1082

**Source object:** [[01 ATT&CK/S0585 - Kerrdown|S0585: Kerrdown]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kerrdown](https://attack.mitre.org/software/S0585) has the ability to determine if the compromised host is running a 32 or 64 bit OS architecture.(Citation: Unit 42 KerrDown February 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7727f1e9-4914-4512-a319-3e5758c47602`.
