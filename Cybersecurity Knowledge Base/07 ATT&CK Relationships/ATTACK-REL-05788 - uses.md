---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1219"
stix_relationship_id: "relationship--9f372adb-777a-4635-9310-cbb8f432f08e"
---
# Relationship 5788: S0266 — uses → T1219

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) uses vncDll module to remote control the victim machine.(Citation: ESET Trickbot Oct 2020)(Citation: Bitdefender Trickbot March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f372adb-777a-4635-9310-cbb8f432f08e`.
