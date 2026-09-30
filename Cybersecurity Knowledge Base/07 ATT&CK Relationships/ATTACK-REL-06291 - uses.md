---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0121"
target_object: "T1204.001"
stix_relationship_id: "relationship--d2ea2645-1940-4776-a874-09309f75636a"
---
# Relationship 6291: G0121 — uses → T1204.001

**Source object:** [[01 ATT&CK/G0121 - Sidewinder|G0121: Sidewinder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sidewinder](https://attack.mitre.org/groups/G0121) has lured targets to click on malicious links to gain execution in the target environment.(Citation: ATT Sidewinder January 2021)(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)(Citation: Cyble Sidewinder September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2ea2645-1940-4776-a874-09309f75636a`.
