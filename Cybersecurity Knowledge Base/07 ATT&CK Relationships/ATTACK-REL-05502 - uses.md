---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "T1018"
stix_relationship_id: "relationship--93a7d544-bed2-4d8c-abda-ab0b82ffa3a9"
---
# Relationship 5502: G0030 — uses → T1018

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used [Ping](https://attack.mitre.org/software/S0097) to identify remote systems.(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93a7d544-bed2-4d8c-abda-ab0b82ffa3a9`.
