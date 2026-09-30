---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1071.001"
stix_relationship_id: "relationship--ecc31d1c-b5ac-4458-b379-a5c003637ee2"
---
# Relationship 6859: S0559 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) communicated via HTTP GET or HTTP POST requests to third party servers for C2.(Citation: FireEye SUNBURST Backdoor December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecc31d1c-b5ac-4458-b379-a5c003637ee2`.
