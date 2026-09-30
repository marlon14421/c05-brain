---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1204.004"
stix_relationship_id: "relationship--94237ba1-b5b3-467c-8394-3414e05763ec"
---
# Relationship 7235: G1052 — uses → T1204.004

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.004 - Malicious Copy and Paste|T1204.004: Malicious Copy and Paste]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has leveraged ClickFix type tactics enticing victims to copy and paste malicious code.(Citation: Sentinel One Contagious Interview ClickFix September 2025)(Citation: Sekoia ClickFake 2025)(Citation: Validin Contagious Interview North Korea ClickFix January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94237ba1-b5b3-467c-8394-3414e05763ec`.
