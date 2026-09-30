---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0119"
target_object: "T1003.005"
stix_relationship_id: "relationship--5c6b3fda-2eec-4c7a-af09-5f880f260085"
---
# Relationship 6110: S0119 — uses → T1003.005

**Source object:** [[01 ATT&CK/S0119 - Cachedump|S0119: Cachedump]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.005 - Cached Domain Credentials|T1003.005: Cached Domain Credentials]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cachedump](https://attack.mitre.org/software/S0119) can extract cached password hashes from cache entry information.(Citation: Mandiant APT1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c6b3fda-2eec-4c7a-af09-5f880f260085`.
