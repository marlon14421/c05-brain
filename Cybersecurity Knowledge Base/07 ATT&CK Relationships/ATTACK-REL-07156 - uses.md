---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0271"
target_object: "T1113"
stix_relationship_id: "relationship--c2888af5-ccdd-43f1-947c-1abd69272ec2"
---
# Relationship 7156: S0271 — uses → T1113

**Source object:** [[01 ATT&CK/S0271 - KEYMARBLE|S0271: KEYMARBLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KEYMARBLE](https://attack.mitre.org/software/S0271) can capture screenshots of the victim’s machine.(Citation: US-CERT KEYMARBLE Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2888af5-ccdd-43f1-947c-1abd69272ec2`.
