---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1042"
target_object: "T1518"
stix_relationship_id: "relationship--2f8394e6-2cf2-473a-b60a-6de2e69c39c8"
---
# Relationship 7865: S1042 — uses → T1518

**Source object:** [[01 ATT&CK/S1042 - SUGARDUMP|S1042: SUGARDUMP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUGARDUMP](https://attack.mitre.org/software/S1042) can identify Chrome, Opera, Edge Chromium, and Firefox browsers, including version number, on a compromised host.(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f8394e6-2cf2-473a-b60a-6de2e69c39c8`.
