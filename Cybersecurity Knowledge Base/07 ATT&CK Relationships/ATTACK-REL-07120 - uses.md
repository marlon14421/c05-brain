---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0610"
target_object: "T1071.001"
stix_relationship_id: "relationship--8c79800f-4f3c-41ad-8d35-7d11c6cd65b3"
---
# Relationship 7120: S0610 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0610 - SideTwist|S0610: SideTwist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SideTwist](https://attack.mitre.org/software/S0610) has used HTTP GET and POST requests over port 443 for C2.(Citation: Check Point APT34 April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c79800f-4f3c-41ad-8d35-7d11c6cd65b3`.
