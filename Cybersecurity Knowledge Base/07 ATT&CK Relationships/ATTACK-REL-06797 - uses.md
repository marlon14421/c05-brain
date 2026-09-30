---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0248"
target_object: "T1056.001"
stix_relationship_id: "relationship--b2f180de-6c03-41cd-a6ed-a49ac674740b"
---
# Relationship 6797: S0248 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0248 - yty|S0248: yty]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[yty](https://attack.mitre.org/software/S0248) uses a keylogger plugin to gather keystrokes.(Citation: ASERT Donot March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b2f180de-6c03-41cd-a6ed-a49ac674740b`.
