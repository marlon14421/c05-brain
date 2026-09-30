---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0085"
target_object: "T1564.008"
stix_relationship_id: "relationship--70a17629-6b01-4764-932b-8be576270329"
---
# Relationship 8113: G0085 — uses → T1564.008

**Source object:** [[01 ATT&CK/G0085 - FIN4|G0085: FIN4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.008 - Email Hiding Rules|T1564.008: Email Hiding Rules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN4](https://attack.mitre.org/groups/G0085) has created rules in victims' Microsoft Outlook accounts to automatically delete emails containing words such as “hacked," "phish," and “malware" in a likely attempt to prevent organizations from communicating about their activities.(Citation: FireEye Hacking FIN4 Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70a17629-6b01-4764-932b-8be576270329`.
