---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0445"
target_object: "T1069"
stix_relationship_id: "relationship--c403720d-da66-45c4-bb35-93b3b35c87c3"
---
# Relationship 7154: S0445 — uses → T1069

**Source object:** [[01 ATT&CK/S0445 - ShimRatReporter|S0445: ShimRatReporter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069 - Permission Groups Discovery|T1069: Permission Groups Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShimRatReporter](https://attack.mitre.org/software/S0445) gathered the local privileges for the infected host.(Citation: FOX-IT May 2016 Mofang)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c403720d-da66-45c4-bb35-93b3b35c87c3`.
