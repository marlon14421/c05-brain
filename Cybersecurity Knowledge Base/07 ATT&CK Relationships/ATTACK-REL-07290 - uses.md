---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0124"
target_object: "T1132.001"
stix_relationship_id: "relationship--4ec9a523-e27f-4984-9bde-4af785e5e75a"
---
# Relationship 7290: S0124 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Responses from the [Pisloader](https://attack.mitre.org/software/S0124) C2 server are base32-encoded.(Citation: Palo Alto DNS Requests)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ec9a523-e27f-4984-9bde-4af785e5e75a`.
