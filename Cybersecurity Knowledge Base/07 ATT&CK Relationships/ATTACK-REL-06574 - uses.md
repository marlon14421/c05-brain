---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0598"
target_object: "T1083"
stix_relationship_id: "relationship--093bc793-3edd-4096-bd7b-aeb5c855128b"
---
# Relationship 6574: S0598 — uses → T1083

**Source object:** [[01 ATT&CK/S0598 - P.A.S. Webshell|S0598: P.A.S. Webshell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[P.A.S. Webshell](https://attack.mitre.org/software/S0598) has the ability to list files and file characteristics including extension, size, ownership, and permissions.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--093bc793-3edd-4096-bd7b-aeb5c855128b`.
