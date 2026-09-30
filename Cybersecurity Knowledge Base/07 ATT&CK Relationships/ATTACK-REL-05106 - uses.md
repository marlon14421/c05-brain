---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1012"
stix_relationship_id: "relationship--5ccac771-a984-4f06-b109-21ea7cd60b02"
---
# Relationship 5106: S0011 — uses → T1012

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) can query the Registry on compromised hosts using RegQueryValueExA .(Citation: CISA MAR-10292089-1.v2 TAIDOOR August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ccac771-a984-4f06-b109-21ea7cd60b02`.
