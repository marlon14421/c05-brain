---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "T1090"
stix_relationship_id: "relationship--bee75401-9e24-4c5d-9203-0b3cdca01cbf"
---
# Relationship 8466: G1006 — uses → T1090

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Earth Lusca](https://attack.mitre.org/groups/G1006) adopted Cloudflare as a proxy for compromised servers.(Citation: TrendMicro EarthLusca 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bee75401-9e24-4c5d-9203-0b3cdca01cbf`.
