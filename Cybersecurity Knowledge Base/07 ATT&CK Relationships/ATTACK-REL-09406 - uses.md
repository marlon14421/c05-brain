---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1164"
target_object: "T1665"
stix_relationship_id: "relationship--f3ab39f8-8b3e-429d-8eea-f264c0668d86"
---
# Relationship 9406: S1164 — uses → T1665

**Source object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1665 - Hide Infrastructure|T1665: Hide Infrastructure]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) attempts to retrieve a non-existent webpage from the command and control server resulting in hidden commands sent via resulting error messages.(Citation: Volexity UPSTYLE 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3ab39f8-8b3e-429d-8eea-f264c0668d86`.
