---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1048"
target_object: "T1059.002"
stix_relationship_id: "relationship--f713c899-8064-4cb2-8068-d5534d1e3d36"
---
# Relationship 8078: S1048 — uses → T1059.002

**Source object:** [[01 ATT&CK/S1048 - macOS.OSAMiner|S1048: macOS.OSAMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.002 - AppleScript|T1059.002: AppleScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[macOS.OSAMiner](https://attack.mitre.org/software/S1048) has used `osascript` to call itself via the `do shell script` command in the [Launch Agent](https://attack.mitre.org/techniques/T1543/001) `.plist` file.(Citation: SentinelLabs reversing run-only applescripts 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f713c899-8064-4cb2-8068-d5534d1e3d36`.
