---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1120"
stix_relationship_id: "relationship--f9c7d0e1-135f-4e21-8251-3049bc24c18d"
---
# Relationship 7400: S0128 — uses → T1120

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADNEWS](https://attack.mitre.org/software/S0128) checks for new hard drives on the victim, such as USB devices, by listening for the WM_DEVICECHANGE window message.(Citation: Forcepoint Monsoon)(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9c7d0e1-135f-4e21-8251-3049bc24c18d`.
