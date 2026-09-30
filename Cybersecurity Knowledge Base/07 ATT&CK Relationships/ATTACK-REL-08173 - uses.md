---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1242"
target_object: "T1106"
stix_relationship_id: "relationship--41b41a39-ff5f-433d-9e2a-3dad3b00d74e"
---
# Relationship 8173: S1242 — uses → T1106

**Source object:** [[01 ATT&CK/S1242 - Qilin|S1242: Qilin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Qilin](https://attack.mitre.org/software/S1242) can attempt to log on to the local computer via `LogonUserW` and use `GetLogicalDrives()` and `EnumResourceW()` for discovery.(Citation: Trend Micro Agenda Ransomware AUG 2022)(Citation: Halcyon Qilin.B OCT 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41b41a39-ff5f-433d-9e2a-3dad3b00d74e`.
