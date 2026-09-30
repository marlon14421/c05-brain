---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0176"
target_object: "T1082"
stix_relationship_id: "relationship--fe786b29-e621-48e2-84b5-aed35e6930fe"
---
# Relationship 6766: S0176 — uses → T1082

**Source object:** [[01 ATT&CK/S0176 - Wingbird|S0176: Wingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wingbird](https://attack.mitre.org/software/S0176) checks the victim OS version after executing to determine where to drop files based on whether the victim is 32-bit or 64-bit.(Citation: Microsoft SIR Vol 21)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe786b29-e621-48e2-84b5-aed35e6930fe`.
