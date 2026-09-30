---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "T1016"
stix_relationship_id: "relationship--b10df154-0c2a-4159-ac0a-1bdaa78f56cb"
---
# Relationship 9482: G0093 — uses → T1016

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GALLIUM](https://attack.mitre.org/groups/G0093) used ipconfig /all to obtain information about the victim network configuration. The group also ran a modified version of [NBTscan](https://attack.mitre.org/software/S0590) to identify available NetBIOS name servers.(Citation: Cybereason Soft Cell June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b10df154-0c2a-4159-ac0a-1bdaa78f56cb`.
