---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0446"
target_object: "T1083"
stix_relationship_id: "relationship--2b196fe7-93e1-4575-8818-578305fc1fae"
---
# Relationship 9827: S0446 — uses → T1083

**Source object:** [[01 ATT&CK/S0446 - Ryuk|S0446: Ryuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ryuk](https://attack.mitre.org/software/S0446) has enumerated files and folders on all mounted drives.(Citation: CrowdStrike Ryuk January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b196fe7-93e1-4575-8818-578305fc1fae`.
