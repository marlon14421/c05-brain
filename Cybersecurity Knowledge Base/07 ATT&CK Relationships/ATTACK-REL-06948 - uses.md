---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0086"
target_object: "T1071.001"
stix_relationship_id: "relationship--fb11df98-790a-4b1c-9ca0-73224226cff3"
---
# Relationship 6948: S0086 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0086 - ZLib|S0086: ZLib]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZLib](https://attack.mitre.org/software/S0086) communicates over HTTP for C2.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb11df98-790a-4b1c-9ca0-73224226cff3`.
