---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0670"
target_object: "T1090"
stix_relationship_id: "relationship--384c2ef7-ae14-4ba2-ad86-bfeea3c14f33"
---
# Relationship 9664: S0670 — uses → T1090

**Source object:** [[01 ATT&CK/S0670 - WarzoneRAT|S0670: WarzoneRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WarzoneRAT](https://attack.mitre.org/software/S0670) has the capability to act as a reverse proxy.(Citation: Check Point Warzone Feb 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--384c2ef7-ae14-4ba2-ad86-bfeea3c14f33`.
