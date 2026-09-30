---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1497.001"
stix_relationship_id: "relationship--270d73c2-27fb-43ac-80b9-d4ea3fef2c06"
---
# Relationship 8772: S0438 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Attor](https://attack.mitre.org/software/S0438) can detect whether it is executed in some virtualized or emulated environment by searching for specific artifacts, such as communication with I/O ports and using VM-specific instructions.(Citation: ESET Attor Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--270d73c2-27fb-43ac-80b9-d4ea3fef2c06`.
