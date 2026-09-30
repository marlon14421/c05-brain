---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0578"
target_object: "T1036.005"
stix_relationship_id: "relationship--8b345565-9a36-4b4a-ace5-b4c50ea894ca"
---
# Relationship 5948: S0578 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0578 - SUPERNOVA|S0578: SUPERNOVA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUPERNOVA](https://attack.mitre.org/software/S0578) has masqueraded as a legitimate SolarWinds DLL.(Citation: Guidepoint SUPERNOVA Dec 2020)(Citation: Unit42 SUPERNOVA Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b345565-9a36-4b4a-ace5-b4c50ea894ca`.
