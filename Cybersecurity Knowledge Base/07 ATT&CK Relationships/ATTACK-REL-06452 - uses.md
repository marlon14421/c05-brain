---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0644"
target_object: "T1027.003"
stix_relationship_id: "relationship--8aca6fab-b526-4716-98e0-1300847b9478"
---
# Relationship 6452: S0644 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0644 - ObliqueRAT|S0644: ObliqueRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ObliqueRAT](https://attack.mitre.org/software/S0644) can hide its payload in BMP images hosted on compromised websites.(Citation: Talos Oblique RAT March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8aca6fab-b526-4716-98e0-1300847b9478`.
