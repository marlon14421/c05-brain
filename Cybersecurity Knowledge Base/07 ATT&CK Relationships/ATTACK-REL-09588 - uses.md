---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0608"
target_object: "T1124"
stix_relationship_id: "relationship--3074f3bd-5a30-4ad2-9a2c-45b1573a454e"
---
# Relationship 9588: S0608 — uses → T1124

**Source object:** [[01 ATT&CK/S0608 - Conficker|S0608: Conficker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conficker](https://attack.mitre.org/software/S0608) uses the current UTC victim system date for domain generation and connects to time servers to determine the current date.(Citation: SANS Conficker)(Citation: Trend Micro Conficker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3074f3bd-5a30-4ad2-9a2c-45b1573a454e`.
