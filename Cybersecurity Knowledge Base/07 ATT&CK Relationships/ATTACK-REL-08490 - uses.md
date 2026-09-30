---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0123"
target_object: "T1505.003"
stix_relationship_id: "relationship--60b2c702-e2f4-47fd-a009-3ba561bceeb8"
---
# Relationship 8490: G0123 — uses → T1505.003

**Source object:** [[01 ATT&CK/G0123 - Volatile Cedar|G0123: Volatile Cedar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volatile Cedar](https://attack.mitre.org/groups/G0123) can inject web shell code into a server.(Citation: CheckPoint Volatile Cedar March 2015)(Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--60b2c702-e2f4-47fd-a009-3ba561bceeb8`.
