---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0630"
target_object: "T1070.004"
stix_relationship_id: "relationship--8a033ef9-10ca-4ed9-9c57-421f769485ae"
---
# Relationship 6430: S0630 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0630 - Nebulae|S0630: Nebulae]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Nebulae](https://attack.mitre.org/software/S0630) has the ability to delete files and directories.(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a033ef9-10ca-4ed9-9c57-421f769485ae`.
