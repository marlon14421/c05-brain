---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0689"
target_object: "T1218.004"
stix_relationship_id: "relationship--4854028c-5924-478c-b274-a37f3ad5d7d2"
---
# Relationship 9947: S0689 — uses → T1218.004

**Source object:** [[01 ATT&CK/S0689 - WhisperGate|S0689: WhisperGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.004 - InstallUtil|T1218.004: InstallUtil]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WhisperGate](https://attack.mitre.org/software/S0689) has used `InstallUtil.exe` as part of its process to disable Windows Defender.(Citation: Unit 42 WhisperGate January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4854028c-5924-478c-b274-a37f3ad5d7d2`.
