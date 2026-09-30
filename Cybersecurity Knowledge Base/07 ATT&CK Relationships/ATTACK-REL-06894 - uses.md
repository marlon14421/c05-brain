---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0260"
target_object: "T1135"
stix_relationship_id: "relationship--e1d0ec8e-0970-4737-9605-1cf8a3ba1371"
---
# Relationship 6894: S0260 — uses → T1135

**Source object:** [[01 ATT&CK/S0260 - InvisiMole|S0260: InvisiMole]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisiMole](https://attack.mitre.org/software/S0260) can gather network share information.(Citation: ESET InvisiMole June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1d0ec8e-0970-4737-9605-1cf8a3ba1371`.
