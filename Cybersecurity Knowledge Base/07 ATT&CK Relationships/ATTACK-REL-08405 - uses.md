---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1588.002"
stix_relationship_id: "relationship--bfa11036-022f-49b3-a6bd-7cf2083a264e"
---
# Relationship 8405: G0050 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) has obtained and used tools such as [Mimikatz](https://attack.mitre.org/software/S0002) and [Cobalt Strike](https://attack.mitre.org/software/S0154), and a variety of other open-source tools from GitHub.(Citation: FireEye APT32 May 2017)(Citation: Cybereason Oceanlotus May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfa11036-022f-49b3-a6bd-7cf2083a264e`.
