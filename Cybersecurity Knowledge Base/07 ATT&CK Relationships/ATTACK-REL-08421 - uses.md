---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0438"
target_object: "T1070.004"
stix_relationship_id: "relationship--d42cdf33-c3c1-4546-9a4f-40f6f64cd524"
---
# Relationship 8421: S0438 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0438 - Attor|S0438: Attor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Attor](https://attack.mitre.org/software/S0438)’s plugin deletes the collected files and log files after exfiltration.(Citation: ESET Attor Oct 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d42cdf33-c3c1-4546-9a4f-40f6f64cd524`.
