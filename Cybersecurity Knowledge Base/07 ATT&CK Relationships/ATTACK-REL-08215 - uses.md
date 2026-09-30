---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0157"
target_object: "T1071.004"
stix_relationship_id: "relationship--a403648d-4c23-46bd-9688-1face1407b42"
---
# Relationship 8215: S0157 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0157 - SOUNDBITE|S0157: SOUNDBITE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SOUNDBITE](https://attack.mitre.org/software/S0157) communicates via DNS for C2.(Citation: FireEye APT32 May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a403648d-4c23-46bd-9688-1face1407b42`.
