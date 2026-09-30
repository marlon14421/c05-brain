---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1041"
stix_relationship_id: "relationship--d361058d-a11b-470d-bed8-44bfd8e50393"
---
# Relationship 8274: G0047 — uses → T1041

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [Gamaredon Group](https://attack.mitre.org/groups/G0047) file stealer can transfer collected files to a hardcoded C2 server.(Citation: Palo Alto Gamaredon Feb 2017)(Citation: ESET Gamaredon Sept2024)(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d361058d-a11b-470d-bed8-44bfd8e50393`.
