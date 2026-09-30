---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1089"
target_object: "T1120"
stix_relationship_id: "relationship--eeb5eeab-3fa1-4670-a7ab-f6a8f7193be9"
---
# Relationship 9996: S1089 — uses → T1120

**Source object:** [[01 ATT&CK/S1089 - SharpDisco|S1089: SharpDisco]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpDisco](https://attack.mitre.org/software/S1089) has dropped a plugin to monitor external drives to `C:\Users\Public\It3.exe`.(Citation: MoustachedBouncer ESET August 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eeb5eeab-3fa1-4670-a7ab-f6a8f7193be9`.
