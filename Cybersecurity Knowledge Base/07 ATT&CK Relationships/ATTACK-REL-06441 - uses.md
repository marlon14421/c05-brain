---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0131"
target_object: "T1083"
stix_relationship_id: "relationship--6cfd1f0f-0355-4b1a-af29-84ed992bbb71"
---
# Relationship 6441: S0131 — uses → T1083

**Source object:** [[01 ATT&CK/S0131 - TINYTYPHON|S0131: TINYTYPHON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TINYTYPHON](https://attack.mitre.org/software/S0131) searches through the drive containing the OS, then all drive letters C through to Z, for documents matching certain extensions.(Citation: Forcepoint Monsoon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cfd1f0f-0355-4b1a-af29-84ed992bbb71`.
