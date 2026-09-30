---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0696"
target_object: "T1041"
stix_relationship_id: "relationship--9ed1920b-595b-40ae-954c-1b4769eac07e"
---
# Relationship 8362: S0696 — uses → T1041

**Source object:** [[01 ATT&CK/S0696 - Flagpro|S0696: Flagpro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flagpro](https://attack.mitre.org/software/S0696) has exfiltrated data to the C2 server.(Citation: NTT Security Flagpro new December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ed1920b-595b-40ae-954c-1b4769eac07e`.
