---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0069"
target_object: "T1083"
stix_relationship_id: "relationship--007cc21a-685a-4701-99c1-20f258cedc7c"
---
# Relationship 9603: S0069 — uses → T1083

**Source object:** [[01 ATT&CK/S0069 - BLACKCOFFEE|S0069: BLACKCOFFEE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLACKCOFFEE](https://attack.mitre.org/software/S0069) has the capability to enumerate files.(Citation: FireEye APT17)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--007cc21a-685a-4701-99c1-20f258cedc7c`.
