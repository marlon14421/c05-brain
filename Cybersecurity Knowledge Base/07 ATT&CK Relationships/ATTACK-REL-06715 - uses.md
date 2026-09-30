---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "T1083"
stix_relationship_id: "relationship--b0a6695b-e5ab-47b3-adfd-4db09c41457e"
---
# Relationship 6715: C0002 — uses → T1083

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors used [zwShell](https://attack.mitre.org/software/S0350) to establish full remote control of the connected machine and browse the victim file system.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0a6695b-e5ab-47b3-adfd-4db09c41457e`.
