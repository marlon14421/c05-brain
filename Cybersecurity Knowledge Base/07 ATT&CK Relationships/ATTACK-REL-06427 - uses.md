---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0078"
target_object: "T1041"
stix_relationship_id: "relationship--ac3b6751-e615-44f6-a086-0c236742d8fd"
---
# Relationship 6427: S0078 — uses → T1041

**Source object:** [[01 ATT&CK/S0078 - Psylo|S0078: Psylo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Psylo](https://attack.mitre.org/software/S0078) exfiltrates data to its C2 server over the same protocol as C2 communications.(Citation: Scarlet Mimic Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac3b6751-e615-44f6-a086-0c236742d8fd`.
