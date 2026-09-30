---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0665"
target_object: "T1112"
stix_relationship_id: "relationship--a5f5eee7-6cc2-4eb4-b918-fc771b927abc"
---
# Relationship 6716: S0665 — uses → T1112

**Source object:** [[01 ATT&CK/S0665 - ThreatNeedle|S0665: ThreatNeedle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThreatNeedle](https://attack.mitre.org/software/S0665) can modify the Registry to save its configuration data as the following RC4-encrypted Registry key: `HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\GameCon`.(Citation: Kaspersky ThreatNeedle Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5f5eee7-6cc2-4eb4-b918-fc771b927abc`.
