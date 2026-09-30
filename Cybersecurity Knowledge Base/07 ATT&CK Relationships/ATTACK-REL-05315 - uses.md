---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0057"
target_object: "T1195.002"
stix_relationship_id: "relationship--51d88fe0-d7b6-42dd-81fd-3b03efdf8f4c"
---
# Relationship 5315: C0057 — uses → T1195.002

**Source object:** [[01 ATT&CK/C0057 - 3CX Supply Chain Attack|C0057: 3CX Supply Chain Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.002 - Compromise Software Supply Chain|T1195.002: Compromise Software Supply Chain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [3CX Supply Chain Attack](https://attack.mitre.org/campaigns/C0057), [AppleJeus](https://attack.mitre.org/groups/G1049) first compromised an “end-of-life" trading software application which was downloaded and executed inside the 3CX enterprise environment. The second compromise modified the Windows and macOS build environments used to distribute the 3CX software to their customer base.(Citation: Mandiant 3cx UNC4736 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51d88fe0-d7b6-42dd-81fd-3b03efdf8f4c`.
