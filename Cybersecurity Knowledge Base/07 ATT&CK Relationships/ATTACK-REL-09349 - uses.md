---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0491"
target_object: "T1119"
stix_relationship_id: "relationship--8ec92ea1-6021-4e0f-9737-826e9f243830"
---
# Relationship 9349: S0491 — uses → T1119

**Source object:** [[01 ATT&CK/S0491 - StrongPity|S0491: StrongPity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrongPity](https://attack.mitre.org/software/S0491) has a file searcher component that can automatically collect and archive files based on a predefined list of file extensions.(Citation: Bitdefender StrongPity June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ec92ea1-6021-4e0f-9737-826e9f243830`.
