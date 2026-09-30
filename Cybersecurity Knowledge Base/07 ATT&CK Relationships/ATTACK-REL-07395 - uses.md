---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1074.001"
stix_relationship_id: "relationship--8c9728bd-f58c-4a78-8b4d-63e8fe8cce31"
---
# Relationship 7395: S1213 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) has configured a custom user data directory such as a folder within `%USERPROFILE%\AppData\Roaming` for staging data.(Citation: TrendMicro LummaStealer 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c9728bd-f58c-4a78-8b4d-63e8fe8cce31`.
