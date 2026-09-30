---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0098"
target_object: "T1123"
stix_relationship_id: "relationship--842f8f4b-9d90-4533-850f-777f33ef8257"
---
# Relationship 9293: S0098 — uses → T1123

**Source object:** [[01 ATT&CK/S0098 - T9000|S0098: T9000]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[T9000](https://attack.mitre.org/software/S0098) uses the Skype API to record audio and video calls. It writes encrypted data to %APPDATA%\Intel\Skype .(Citation: Palo Alto T9000 Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--842f8f4b-9d90-4533-850f-777f33ef8257`.
