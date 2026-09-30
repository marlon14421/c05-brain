---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1218.015"
stix_relationship_id: "relationship--4d6143a5-73dc-4e72-8677-6b26dbfaa114"
---
# Relationship 9574: S1213 — uses → T1218.015

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.015 - Electron Applications|T1218.015: Electron Applications]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) as leveraged Electron Applications to disable GPU sandboxing to avoid detection by security software.(Citation: TrendMicro LummaStealer 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4d6143a5-73dc-4e72-8677-6b26dbfaa114`.
