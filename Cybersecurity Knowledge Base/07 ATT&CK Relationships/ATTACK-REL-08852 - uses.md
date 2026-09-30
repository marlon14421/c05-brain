---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0375"
target_object: "T1041"
stix_relationship_id: "relationship--551c4e98-3dfb-472b-8fa8-6a8961dfd418"
---
# Relationship 8852: S0375 — uses → T1041

**Source object:** [[01 ATT&CK/S0375 - Remexi|S0375: Remexi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remexi](https://attack.mitre.org/software/S0375) performs exfiltration over [BITSAdmin](https://attack.mitre.org/software/S0190), which is also used for the C2 channel.(Citation: Securelist Remexi Jan 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--551c4e98-3dfb-472b-8fa8-6a8961dfd418`.
