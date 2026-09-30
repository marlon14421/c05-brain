---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0066"
target_object: "T1204.002"
stix_relationship_id: "relationship--1262d88d-0eb1-4d19-b84a-9793ef3e4d03"
---
# Relationship 7771: G0066 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0066 - Elderwood|G0066: Elderwood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Elderwood](https://attack.mitre.org/groups/G0066) has leveraged multiple types of spearphishing in order to attempt to get a user to open attachments.(Citation: Symantec Elderwood Sept 2012)(Citation: CSM Elderwood Sept 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1262d88d-0eb1-4d19-b84a-9793ef3e4d03`.
