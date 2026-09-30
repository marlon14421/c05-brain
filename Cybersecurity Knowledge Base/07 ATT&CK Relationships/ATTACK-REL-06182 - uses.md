---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0199"
target_object: "T1547.001"
stix_relationship_id: "relationship--f2d1bf8c-6541-40af-8c84-48c7570fb50b"
---
# Relationship 6182: S0199 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0199 - TURNEDUP|S0199: TURNEDUP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TURNEDUP](https://attack.mitre.org/software/S0199) is capable of writing to a Registry Run key to establish.(Citation: CyberBit Early Bird Apr 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2d1bf8c-6541-40af-8c84-48c7570fb50b`.
