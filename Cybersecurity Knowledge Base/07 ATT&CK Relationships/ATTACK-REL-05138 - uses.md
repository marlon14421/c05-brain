---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1016"
target_object: "T1555.001"
stix_relationship_id: "relationship--86fd8738-ab8f-4b80-8c8d-fc80df9e2c07"
---
# Relationship 5138: S1016 — uses → T1555.001

**Source object:** [[01 ATT&CK/S1016 - MacMa|S1016: MacMa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MacMa](https://attack.mitre.org/software/S1016) can dump credentials from the macOS keychain.(Citation: ESET DazzleSpy Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86fd8738-ab8f-4b80-8c8d-fc80df9e2c07`.
