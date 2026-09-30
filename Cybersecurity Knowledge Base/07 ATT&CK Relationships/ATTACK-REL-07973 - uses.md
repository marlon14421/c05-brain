---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0139"
target_object: "T1564.004"
stix_relationship_id: "relationship--91f59958-db5f-429c-9608-a033ea68486b"
---
# Relationship 7973: S0139 — uses → T1564.004

**Source object:** [[01 ATT&CK/S0139 - PowerDuke|S0139: PowerDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.004 - NTFS File Attributes|T1564.004: NTFS File Attributes]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerDuke](https://attack.mitre.org/software/S0139) hides many of its backdoor payloads in an alternate data stream (ADS).(Citation: Volexity PowerDuke November 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91f59958-db5f-429c-9608-a033ea68486b`.
