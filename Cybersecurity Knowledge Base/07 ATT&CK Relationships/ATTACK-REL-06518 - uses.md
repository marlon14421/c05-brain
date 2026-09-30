---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0050"
target_object: "T1543.003"
stix_relationship_id: "relationship--17629f20-194c-48cb-aa1c-b3da2b6f06ba"
---
# Relationship 6518: S0050 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0050 - CosmicDuke|S0050: CosmicDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CosmicDuke](https://attack.mitre.org/software/S0050) uses Windows services typically named "javamtsup" for persistence.(Citation: F-Secure Cosmicduke)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17629f20-194c-48cb-aa1c-b3da2b6f06ba`.
