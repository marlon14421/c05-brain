---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1036.005"
stix_relationship_id: "relationship--78ba82a1-e803-42c1-b112-ce999369d348"
---
# Relationship 6854: S0534 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Bazar](https://attack.mitre.org/software/S0534) loader has named malicious shortcuts "adobe" and mimicked communications software.(Citation: Cybereason Bazar July 2020)(Citation: NCC Group Team9 June 2020)(Citation: CrowdStrike Wizard Spider October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78ba82a1-e803-42c1-b112-ce999369d348`.
