---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0176"
target_object: "T1070.004"
stix_relationship_id: "relationship--2e5039ef-913f-4808-9685-32f64f4dbf49"
---
# Relationship 8545: S0176 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0176 - Wingbird|S0176: Wingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wingbird](https://attack.mitre.org/software/S0176) deletes its payload along with the payload's parent process after it finishes copying files.(Citation: Microsoft SIR Vol 21)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e5039ef-913f-4808-9685-32f64f4dbf49`.
