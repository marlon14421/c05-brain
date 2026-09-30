---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1049"
target_object: "T1543.003"
stix_relationship_id: "relationship--8b580ccf-247a-4ebb-97f3-8d143ed1150c"
---
# Relationship 8489: S1049 — uses → T1543.003

**Source object:** [[01 ATT&CK/S1049 - SUGARUSH|S1049: SUGARUSH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUGARUSH](https://attack.mitre.org/software/S1049) has created a service named `Service1` for persistence.(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b580ccf-247a-4ebb-97f3-8d143ed1150c`.
