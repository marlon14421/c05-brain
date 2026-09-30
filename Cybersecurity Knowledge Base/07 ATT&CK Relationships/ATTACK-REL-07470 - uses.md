---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0615"
target_object: "T1036"
stix_relationship_id: "relationship--f40170e7-5246-442e-95ad-1b810107b8b8"
---
# Relationship 7470: S0615 — uses → T1036

**Source object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SombRAT](https://attack.mitre.org/software/S0615) can use a legitimate process name to hide itself.(Citation: CISA AR21-126A FIVEHANDS May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f40170e7-5246-442e-95ad-1b810107b8b8`.
