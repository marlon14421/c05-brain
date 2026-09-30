---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1035"
target_object: "T1547.001"
stix_relationship_id: "relationship--70613a9f-e8c2-44ba-a238-34acb0b7e5b8"
---
# Relationship 8261: S1035 — uses → T1547.001

**Source object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Small Sieve](https://attack.mitre.org/software/S1035) has the ability to add itself to `HKCU\Software\Microsoft\Windows\CurrentVersion\Run\OutlookMicrosift` for persistence.(Citation: NCSC GCHQ Small Sieve Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70613a9f-e8c2-44ba-a238-34acb0b7e5b8`.
