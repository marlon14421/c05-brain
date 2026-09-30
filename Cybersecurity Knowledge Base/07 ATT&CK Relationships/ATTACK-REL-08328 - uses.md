---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1486"
stix_relationship_id: "relationship--cb043548-a193-4ade-b69d-d83e3378d255"
---
# Relationship 8328: S0658 — uses → T1486

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XCSSET](https://attack.mitre.org/software/S0658) performs AES-CBC encryption on files under ~/Documents , ~/Downloads , and ~/Desktop with a fixed key and renames files to give them a .enc extension. Only files with sizes less than 500MB are encrypted.(Citation: trendmicro xcsset xcode project 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb043548-a193-4ade-b69d-d83e3378d255`.
