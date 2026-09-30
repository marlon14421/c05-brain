---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1035"
target_object: "T1033"
stix_relationship_id: "relationship--82927a23-3e5e-4892-b788-c35cc6e649a5"
---
# Relationship 6457: S1035 — uses → T1033

**Source object:** [[01 ATT&CK/S1035 - Small Sieve|S1035: Small Sieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Small Sieve](https://attack.mitre.org/software/S1035) can obtain the id of a logged in user.(Citation: NCSC GCHQ Small Sieve Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82927a23-3e5e-4892-b788-c35cc6e649a5`.
