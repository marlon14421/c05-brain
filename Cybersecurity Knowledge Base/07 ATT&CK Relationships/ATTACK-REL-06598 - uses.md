---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0635"
target_object: "T1036"
stix_relationship_id: "relationship--84be9d61-ec20-4066-8c99-b99d9127fce2"
---
# Relationship 6598: S0635 — uses → T1036

**Source object:** [[01 ATT&CK/S0635 - BoomBox|S0635: BoomBox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BoomBox](https://attack.mitre.org/software/S0635) has the ability to mask malicious data strings as PDF files.(Citation: MSTIC Nobelium Toolset May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84be9d61-ec20-4066-8c99-b99d9127fce2`.
