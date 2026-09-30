---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0036"
target_object: "T1566.002"
stix_relationship_id: "relationship--ff1d0eba-a675-4ebb-a9a3-b28b8d3a15fc"
---
# Relationship 7451: C0036 — uses → T1566.002

**Source object:** [[01 ATT&CK/C0036 - Pikabot Distribution February 2024|C0036: Pikabot Distribution February 2024]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pikabot Distribution February 2024](https://attack.mitre.org/campaigns/C0036) utilized emails with hyperlinks leading to malicious ZIP archive files containing scripts to download and install [Pikabot](https://attack.mitre.org/software/S1145).(Citation: Elastic Pikabot 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff1d0eba-a675-4ebb-a9a3-b28b8d3a15fc`.
