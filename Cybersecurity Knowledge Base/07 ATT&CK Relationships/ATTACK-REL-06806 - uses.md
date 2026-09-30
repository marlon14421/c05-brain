---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0644"
target_object: "T1057"
stix_relationship_id: "relationship--c5dffed7-7e56-4cee-8f96-065b4718000d"
---
# Relationship 6806: S0644 — uses → T1057

**Source object:** [[01 ATT&CK/S0644 - ObliqueRAT|S0644: ObliqueRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ObliqueRAT](https://attack.mitre.org/software/S0644) can check for blocklisted process names on a compromised host.(Citation: Talos Oblique RAT March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5dffed7-7e56-4cee-8f96-065b4718000d`.
