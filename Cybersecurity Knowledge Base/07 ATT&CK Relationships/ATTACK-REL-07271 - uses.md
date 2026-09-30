---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0039"
target_object: "T1046"
stix_relationship_id: "relationship--9b360cf4-4600-4ea8-a28c-99d91e0d1734"
---
# Relationship 7271: G0039 — uses → T1046

**Source object:** [[01 ATT&CK/G0039 - Suckfly|G0039: Suckfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Suckfly](https://attack.mitre.org/groups/G0039) the victim's internal network for hosts with ports 8080, 5900, and 40 open.(Citation: Symantec Suckfly May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b360cf4-4600-4ea8-a28c-99d91e0d1734`.
