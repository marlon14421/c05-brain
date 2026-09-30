---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0384"
target_object: "T1090.003"
stix_relationship_id: "relationship--e496b3d5-3608-49e6-9567-86b370abeeb3"
---
# Relationship 8659: S0384 — uses → T1090.003

**Source object:** [[01 ATT&CK/S0384 - Dridex|S0384: Dridex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dridex](https://attack.mitre.org/software/S0384) can use multiple layers of proxy servers to hide terminal nodes in its infrastructure.(Citation: Checkpoint Dridex Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e496b3d5-3608-49e6-9567-86b370abeeb3`.
