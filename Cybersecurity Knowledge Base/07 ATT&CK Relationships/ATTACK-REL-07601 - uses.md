---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0413"
target_object: "T1110.003"
stix_relationship_id: "relationship--b85cff83-6468-4c63-9b25-4ac75fcb0e10"
---
# Relationship 7601: S0413 — uses → T1110.003

**Source object:** [[01 ATT&CK/S0413 - MailSniper|S0413: MailSniper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.003 - Password Spraying|T1110.003: Password Spraying]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MailSniper](https://attack.mitre.org/software/S0413) can be used for password spraying against Exchange and Office 365.(Citation: GitHub MailSniper)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b85cff83-6468-4c63-9b25-4ac75fcb0e10`.
