---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0128"
target_object: "T1132"
stix_relationship_id: "relationship--3884be12-f73f-4f9b-875e-68d40798faf6"
---
# Relationship 6278: S0128 — uses → T1132

**Source object:** [[01 ATT&CK/S0128 - BADNEWS|S0128: BADNEWS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132 - Data Encoding|T1132: Data Encoding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

After encrypting C2 data, [BADNEWS](https://attack.mitre.org/software/S0128) converts it into a hexadecimal representation and then encodes it into base64.(Citation: Forcepoint Monsoon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3884be12-f73f-4f9b-875e-68d40798faf6`.
