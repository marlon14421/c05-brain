---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1107"
target_object: "T1090.003"
stix_relationship_id: "relationship--944ddd08-e535-4f66-aec2-051f8b35ae80"
---
# Relationship 8111: S1107 — uses → T1090.003

**Source object:** [[01 ATT&CK/S1107 - NKAbuse|S1107: NKAbuse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NKAbuse](https://attack.mitre.org/software/S1107) has abused the NKN public blockchain protocol for its C2 communications.(Citation: NKAbuse BC)(Citation: NKAbuse SL)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--944ddd08-e535-4f66-aec2-051f8b35ae80`.
