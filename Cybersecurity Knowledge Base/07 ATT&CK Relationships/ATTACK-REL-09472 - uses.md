---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0048"
target_object: "T1090"
stix_relationship_id: "relationship--30bff73c-7c73-4d18-84ab-bf5033f63d34"
---
# Relationship 9472: C0048 — uses → T1090

**Source object:** [[01 ATT&CK/C0048 - Operation MidnightEclipse|C0048: Operation MidnightEclipse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation MidnightEclipse](https://attack.mitre.org/campaigns/C0048), threat actors used the GO Simple Tunnel reverse proxy tool.(Citation: Volexity UPSTYLE 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30bff73c-7c73-4d18-84ab-bf5033f63d34`.
