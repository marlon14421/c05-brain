---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1057"
stix_relationship_id: "relationship--23c76193-d7e8-4dca-a9d6-e9b6b0bacfea"
---
# Relationship 5559: S1185 — uses → T1057

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If sent the command `16002`, [LightSpy](https://attack.mitre.org/software/S1185) uses the `NSWorkspace runningApplications()` method to collect the process ID, path to the executable, bundle information, and the filename of the executable for all running applications.(Citation: Huntress LightSpy macOS 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23c76193-d7e8-4dca-a9d6-e9b6b0bacfea`.
