---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "S0032"
stix_relationship_id: "relationship--37e520de-fe38-450b-a30e-3372f7ff3a4f"
---
# Relationship 9868: G0096 — uses → S0032

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: FireEye APT41 Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37e520de-fe38-450b-a30e-3372f7ff3a4f`.
