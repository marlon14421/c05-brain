---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1560"
stix_relationship_id: "relationship--43b6c74f-57ee-4cf8-acf8-97cbaa85db38"
---
# Relationship 7852: S9043 — uses → T1560

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has compressed collected credentials to reduce transmission size and to make string content harder to detect in memory forensics captures.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43b6c74f-57ee-4cf8-acf8-97cbaa85db38`.
