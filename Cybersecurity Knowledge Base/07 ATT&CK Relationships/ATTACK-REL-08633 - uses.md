---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1211"
target_object: "T1543.003"
stix_relationship_id: "relationship--9590abd3-381a-4bc0-ad76-7fbc3339566b"
---
# Relationship 8633: S1211 — uses → T1543.003

**Source object:** [[01 ATT&CK/S1211 - Hannotog|S1211: Hannotog]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hannotog](https://attack.mitre.org/software/S1211) creates a new service for persistence.(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9590abd3-381a-4bc0-ad76-7fbc3339566b`.
