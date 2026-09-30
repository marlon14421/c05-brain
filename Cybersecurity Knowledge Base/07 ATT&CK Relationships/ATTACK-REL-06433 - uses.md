---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0024"
target_object: "T1547.001"
stix_relationship_id: "relationship--55120727-0b7f-4d6a-a881-d17bdc9c85ba"
---
# Relationship 6433: G0024 — uses → T1547.001

**Source object:** [[01 ATT&CK/G0024 - Putter Panda|G0024: Putter Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A dropper used by [Putter Panda](https://attack.mitre.org/groups/G0024) installs itself into the ASEP Registry key HKCU\Software\Microsoft\Windows\CurrentVersion\Run with a value named McUpdate.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--55120727-0b7f-4d6a-a881-d17bdc9c85ba`.
