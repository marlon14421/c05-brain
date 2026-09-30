---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0095"
target_object: "T1059.006"
stix_relationship_id: "relationship--532feb00-b2ba-4cf6-81e8-57750d30b039"
---
# Relationship 8917: G0095 — uses → T1059.006

**Source object:** [[01 ATT&CK/G0095 - Machete|G0095: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/groups/G0095) used multiple compiled Python scripts on the victim’s system. [Machete](https://attack.mitre.org/groups/G0095)'s main backdoor [Machete](https://attack.mitre.org/software/S0409) is also written in Python.(Citation: Cylance Machete Mar 2017)(Citation: ESET Machete July 2019)(Citation: 360 Machete Sep 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--532feb00-b2ba-4cf6-81e8-57750d30b039`.
