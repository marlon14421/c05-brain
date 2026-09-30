---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1036"
stix_relationship_id: "relationship--5cd22798-0d6e-4bed-b139-c46a4cfa87a5"
---
# Relationship 5279: S1240 — uses → T1036

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) malware has masqueraded as legitimate software such as "PDF Converter Software" which has been distributed through poisoned search engine results often resembling legitimate software lures with the combination of typo squatted domains.(Citation: Kroll RedLine Stealer August 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5cd22798-0d6e-4bed-b139-c46a4cfa87a5`.
