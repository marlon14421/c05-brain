---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0665"
target_object: "T1027.011"
stix_relationship_id: "relationship--9de8aee7-1867-48a4-9a78-3076853e43ac"
---
# Relationship 7391: S0665 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0665 - ThreatNeedle|S0665: ThreatNeedle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThreatNeedle](https://attack.mitre.org/software/S0665) can save its configuration data as a RC4-encrypted Registry key under `HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\GameCon`.(Citation: Kaspersky ThreatNeedle Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9de8aee7-1867-48a4-9a78-3076853e43ac`.
