---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0657"
target_object: "T1082"
stix_relationship_id: "relationship--1da27474-f902-419e-97a9-1fba8743cce8"
---
# Relationship 5145: S0657 — uses → T1082

**Source object:** [[01 ATT&CK/S0657 - BLUELIGHT|S0657: BLUELIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLUELIGHT](https://attack.mitre.org/software/S0657) has collected the computer name and OS version from victim machines.(Citation: Volexity InkySquid BLUELIGHT August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1da27474-f902-419e-97a9-1fba8743cce8`.
