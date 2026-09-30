---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0414"
target_object: "T1056.001"
stix_relationship_id: "relationship--3a0c8e81-6110-4cf3-a965-b700e00fd66c"
---
# Relationship 8440: S0414 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0414 - BabyShark|S0414: BabyShark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BabyShark](https://attack.mitre.org/software/S0414) has a [PowerShell](https://attack.mitre.org/techniques/T1059/001)-based remote administration ability that can implement a PowerShell or C# based keylogger.(Citation: Unit42 BabyShark Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a0c8e81-6110-4cf3-a965-b700e00fd66c`.
