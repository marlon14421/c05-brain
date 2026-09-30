---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1564.009"
stix_relationship_id: "relationship--4efc1b5d-c1cb-4d94-a4b8-6b0b2b857788"
---
# Relationship 7725: S0276 — uses → T1564.009

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.009 - Resource Forking|T1564.009: Resource Forking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) uses a resource fork to present a macOS JPEG or text file icon rather than the executable's icon assigned by the operating system.(Citation: OSX Keydnap malware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4efc1b5d-c1cb-4d94-a4b8-6b0b2b857788`.
