---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0629"
target_object: "T1007"
stix_relationship_id: "relationship--56b8f3d1-c08e-42a1-8d14-b961391eaaa7"
---
# Relationship 7345: S0629 — uses → T1007

**Source object:** [[01 ATT&CK/S0629 - RainyDay|S0629: RainyDay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RainyDay](https://attack.mitre.org/software/S0629) can create and register a service for execution.(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56b8f3d1-c08e-42a1-8d14-b961391eaaa7`.
