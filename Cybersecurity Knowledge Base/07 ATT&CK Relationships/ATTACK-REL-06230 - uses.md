---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0065"
target_object: "S0183"
stix_relationship_id: "relationship--ec9a7e1d-53f8-4a79-a5dd-a5890bf421ba"
---
# Relationship 6230: G0065 — uses → S0183

**Source object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0183 - Tor|S0183: Tor]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CISA AA21-200A APT40 July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec9a7e1d-53f8-4a79-a5dd-a5890bf421ba`.
