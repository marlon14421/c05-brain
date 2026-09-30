---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0128"
target_object: "T1036.004"
stix_relationship_id: "relationship--baefaf38-da2d-4864-9c96-3bf2352bc20b"
---
# Relationship 7212: G0128 — uses → T1036.004

**Source object:** [[01 ATT&CK/G0128 - ZIRCONIUM|G0128: ZIRCONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has created a run key named Dropbox Update Setup to mask a persistence mechanism for a malicious binary.(Citation: Zscaler APT31 Covid-19 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--baefaf38-da2d-4864-9c96-3bf2352bc20b`.
