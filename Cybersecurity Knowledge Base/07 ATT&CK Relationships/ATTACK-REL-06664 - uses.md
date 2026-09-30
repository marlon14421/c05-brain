---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1087"
target_object: "T1057"
stix_relationship_id: "relationship--d531b421-7347-4dd6-9a98-0b05e6421b40"
---
# Relationship 6664: S1087 — uses → T1057

**Source object:** [[01 ATT&CK/S1087 - AsyncRAT|S1087: AsyncRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AsyncRAT](https://attack.mitre.org/software/S1087) can examine running processes to determine if a debugger is present.(Citation: Telefonica Snip3 December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d531b421-7347-4dd6-9a98-0b05e6421b40`.
