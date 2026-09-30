---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0261"
target_object: "T1036.004"
stix_relationship_id: "relationship--b4c195b6-7b1f-4320-8040-e91c11ec8cbb"
---
# Relationship 9329: S0261 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0261 - Catchamas|S0261: Catchamas]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Catchamas](https://attack.mitre.org/software/S0261) adds a new service named NetAdapter in an apparent attempt to masquerade as a legitimate service.(Citation: Symantec Catchamas April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b4c195b6-7b1f-4320-8040-e91c11ec8cbb`.
