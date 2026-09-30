---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0271"
target_object: "T1083"
stix_relationship_id: "relationship--30ab931e-9cc1-4e95-a3f5-364be094b54e"
---
# Relationship 7167: S0271 — uses → T1083

**Source object:** [[01 ATT&CK/S0271 - KEYMARBLE|S0271: KEYMARBLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KEYMARBLE](https://attack.mitre.org/software/S0271) has a command to search for files on the victim’s machine.(Citation: US-CERT KEYMARBLE Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30ab931e-9cc1-4e95-a3f5-364be094b54e`.
