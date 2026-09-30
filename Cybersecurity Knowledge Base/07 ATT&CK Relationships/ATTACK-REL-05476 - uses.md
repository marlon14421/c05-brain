---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0263"
target_object: "T1083"
stix_relationship_id: "relationship--fe1c5e06-ea4b-4286-af2d-984a095f7924"
---
# Relationship 5476: S0263 — uses → T1083

**Source object:** [[01 ATT&CK/S0263 - TYPEFRAME|S0263: TYPEFRAME]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TYPEFRAME](https://attack.mitre.org/software/S0263) can search directories for files on the victim’s machine.(Citation: US-CERT TYPEFRAME June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe1c5e06-ea4b-4286-af2d-984a095f7924`.
