---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1124"
stix_relationship_id: "relationship--290c5e81-69e8-4ca1-983e-b24e675e7f89"
---
# Relationship 6130: S9042 — uses → T1124

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has checked if the target system’s time zone is “Asia/Tehran” or “Iran.”(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Aikido CanisterWorm MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--290c5e81-69e8-4ca1-983e-b24e675e7f89`.
