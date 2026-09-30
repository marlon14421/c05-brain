---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0005"
target_object: "S0003"
stix_relationship_id: "relationship--d242dc5a-3969-498c-b7eb-5d850e7d384d"
---
# Relationship 9862: G0005 — uses → S0003

**Source object:** [[01 ATT&CK/G0005 - APT12|G0005: APT12]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0003 - RIPTIDE|S0003: RIPTIDE]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Moran 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d242dc5a-3969-498c-b7eb-5d850e7d384d`.
