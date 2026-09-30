---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1082"
stix_relationship_id: "relationship--afe95822-7845-4f16-b50c-62f428c59697"
---
# Relationship 9955: S1240 — uses → T1082

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) can collect information about the local system.(Citation: Kroll RedLine Stealer August 2024)(Citation: Proofpoint RedLine Stealer March 2020)(Citation: Splunk RedLine Stealer June 2023)(Citation: Veriti RedLine Stealer MAAS April 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afe95822-7845-4f16-b50c-62f428c59697`.
