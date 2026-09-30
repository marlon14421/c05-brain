---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9022"
target_object: "T1552.006"
stix_relationship_id: "relationship--39d06f63-a10e-4882-91f0-7f96a6ad74e8"
---
# Relationship 5762: S9022 — uses → T1552.006

**Source object:** [[01 ATT&CK/S9022 - MirrorStealer|S9022: MirrorStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.006 - Group Policy Preferences|T1552.006: Group Policy Preferences]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorStealer](https://attack.mitre.org/software/S9022) can target Group Policy Preferences for credentials.(Citation: Trend Micro Earth Kasha NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39d06f63-a10e-4882-91f0-7f96a6ad74e8`.
