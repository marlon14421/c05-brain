---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0653"
target_object: "T1071.001"
stix_relationship_id: "relationship--0a6b2a04-b01a-45a6-a0da-221dcdcf1c51"
---
# Relationship 5938: S0653 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0653 - xCaon|S0653: xCaon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[xCaon](https://attack.mitre.org/software/S0653) has communicated with the C2 server by sending POST requests over HTTP.(Citation: Checkpoint IndigoZebra July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a6b2a04-b01a-45a6-a0da-221dcdcf1c51`.
