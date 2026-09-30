---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0074"
target_object: "T1547.001"
stix_relationship_id: "relationship--384c75e4-04e7-4ff8-9da6-0c8a03cb7a61"
---
# Relationship 5536: S0074 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0074 - Sakula|S0074: Sakula]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Most [Sakula](https://attack.mitre.org/software/S0074) samples maintain persistence by setting the Registry Run key SOFTWARE\Microsoft\Windows\CurrentVersion\Run\ in the HKLM or HKCU hive, with the Registry value and file name varying by sample.(Citation: Dell Sakula)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--384c75e4-04e7-4ff8-9da6-0c8a03cb7a61`.
