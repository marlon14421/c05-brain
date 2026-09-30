---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0567"
target_object: "T1083"
stix_relationship_id: "relationship--9866c9ca-d769-458c-9797-112beb97498d"
---
# Relationship 9031: S0567 — uses → T1083

**Source object:** [[01 ATT&CK/S0567 - Dtrack|S0567: Dtrack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dtrack](https://attack.mitre.org/software/S0567) can list files on available disk volumes.(Citation: Securelist Dtrack)(Citation: CyberBit Dtrack)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9866c9ca-d769-458c-9797-112beb97498d`.
