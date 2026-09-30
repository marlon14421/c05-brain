---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0276"
target_object: "T1543.001"
stix_relationship_id: "relationship--feccb439-0a34-4224-ba12-62e11215d5a5"
---
# Relationship 5537: S0276 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0276 - Keydnap|S0276: Keydnap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Keydnap](https://attack.mitre.org/software/S0276) uses a Launch Agent to persist.(Citation: synack 2016 review)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--feccb439-0a34-4224-ba12-62e11215d5a5`.
