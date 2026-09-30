---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1123"
stix_relationship_id: "relationship--2a32c434-c3ef-42ee-a0b6-c64c589355c3"
---
# Relationship 5006: S0194 — uses → T1123

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194)'s Get-MicrophoneAudio Exfiltration module can record system microphone audio.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a32c434-c3ef-42ee-a0b6-c64c589355c3`.
