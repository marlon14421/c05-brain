---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0015"
target_object: "T1547.001"
stix_relationship_id: "relationship--4ad60c58-2665-4c4b-a9e8-5cd0042e45bb"
---
# Relationship 9680: S0015 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0015 - Ixeshe|S0015: Ixeshe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ixeshe](https://attack.mitre.org/software/S0015) can achieve persistence by adding itself to the HKCU\Software\Microsoft\Windows\CurrentVersion\Run Registry key.(Citation: Trend Micro IXESHE 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ad60c58-2665-4c4b-a9e8-5cd0042e45bb`.
