---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0644"
target_object: "T1125"
stix_relationship_id: "relationship--e31c20e8-f6f7-4ebb-89e0-51c34597c379"
---
# Relationship 6587: S0644 — uses → T1125

**Source object:** [[01 ATT&CK/S0644 - ObliqueRAT|S0644: ObliqueRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1125 - Video Capture|T1125: Video Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ObliqueRAT](https://attack.mitre.org/software/S0644) can capture images from webcams on compromised hosts.(Citation: Talos Oblique RAT March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e31c20e8-f6f7-4ebb-89e0-51c34597c379`.
