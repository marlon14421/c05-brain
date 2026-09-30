---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1564.001"
stix_relationship_id: "relationship--9b2a5ea0-3199-44ee-a5a5-959e95d3a2e5"
---
# Relationship 8083: S0484 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carberp](https://attack.mitre.org/software/S0484) has created a hidden file in the Startup folder of the current user.(Citation: Trusteer Carberp October 2010)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b2a5ea0-3199-44ee-a5a5-959e95d3a2e5`.
