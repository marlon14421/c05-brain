---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0021"
target_object: "T1218.007"
stix_relationship_id: "relationship--0da9ee24-37ac-4568-b1fc-d784f05dfc97"
---
# Relationship 7897: G0021 — uses → T1218.007

**Source object:** [[01 ATT&CK/G0021 - Molerats|G0021: Molerats]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Molerats](https://attack.mitre.org/groups/G0021) has used msiexec.exe to execute an MSI payload.(Citation: Unit42 Molerat Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0da9ee24-37ac-4568-b1fc-d784f05dfc97`.
