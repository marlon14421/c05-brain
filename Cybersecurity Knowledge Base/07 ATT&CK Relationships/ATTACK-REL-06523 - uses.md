---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0582"
target_object: "T1547.001"
stix_relationship_id: "relationship--928977f5-9602-4020-b8e8-31a8e3881225"
---
# Relationship 6523: S0582 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0582 - LookBack|S0582: LookBack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LookBack](https://attack.mitre.org/software/S0582) sets up a Registry Run key to establish a persistence mechanism.(Citation: Proofpoint LookBack Malware Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--928977f5-9602-4020-b8e8-31a8e3881225`.
