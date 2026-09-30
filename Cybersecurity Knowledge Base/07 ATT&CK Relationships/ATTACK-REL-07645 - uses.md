---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1106"
stix_relationship_id: "relationship--5580b0f6-7679-46c3-adb5-270c87f8ef69"
---
# Relationship 7645: S0689 — uses → T1106

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) has used the `ExitWindowsEx` to flush file buffers to disk and stop running processes and other API calls.(Citation: Cisco Ukraine Wipers January 2022)(Citation: RecordedFuture WhisperGate Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5580b0f6-7679-46c3-adb5-270c87f8ef69`.
