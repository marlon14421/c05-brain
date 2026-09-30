---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0385"
target_object: "T1120"
stix_relationship_id: "relationship--30180ece-4504-4b6a-9182-5a2fbe3292df"
---
# Relationship 9548: S0385 — uses → T1120

**Source object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1120 - Peripheral Device Discovery|T1120: Peripheral Device Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[njRAT](https://attack.mitre.org/software/S0385) will attempt to detect if the victim system has a camera during the initial infection. [njRAT](https://attack.mitre.org/software/S0385) can also detect any removable drives connected to the system.(Citation: Fidelis njRAT June 2013)(Citation: Trend Micro njRAT 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30180ece-4504-4b6a-9182-5a2fbe3292df`.
