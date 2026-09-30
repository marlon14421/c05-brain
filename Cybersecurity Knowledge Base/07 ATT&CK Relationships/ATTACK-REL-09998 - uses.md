---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0274"
target_object: "T1569.001"
stix_relationship_id: "relationship--bb371ea5-33c4-42e7-bcb0-3374240da553"
---
# Relationship 9998: S0274 — uses → T1569.001

**Source object:** [[01 ATT&CK/S0274 - Calisto|S0274: Calisto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.001 - Launchctl|T1569.001: Launchctl]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Calisto](https://attack.mitre.org/software/S0274) uses launchctl to enable screen sharing on the victim’s machine.(Citation: Securelist Calisto July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb371ea5-33c4-42e7-bcb0-3374240da553`.
