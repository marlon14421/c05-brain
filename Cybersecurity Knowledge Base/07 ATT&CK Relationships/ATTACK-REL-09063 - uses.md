---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0278"
target_object: "T1564.001"
stix_relationship_id: "relationship--b1d1e98b-e3fe-43d8-8b6d-810d8bc6cfab"
---
# Relationship 9063: S0278 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0278 - iKitten|S0278: iKitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[iKitten](https://attack.mitre.org/software/S0278) saves itself with a leading "." so that it's hidden from users by default.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1d1e98b-e3fe-43d8-8b6d-810d8bc6cfab`.
