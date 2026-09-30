---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1048"
stix_relationship_id: "relationship--1b29f7b8-78fe-4bae-b943-59641a12a023"
---
# Relationship 9450: S0428 — uses → T1048

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048 - Exfiltration Over Alternative Protocol|T1048: Exfiltration Over Alternative Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) has used a .NET tool named dog.exe to exiltrate information over an e-mail account.(Citation: Talos PoetRAT April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b29f7b8-78fe-4bae-b943-59641a12a023`.
