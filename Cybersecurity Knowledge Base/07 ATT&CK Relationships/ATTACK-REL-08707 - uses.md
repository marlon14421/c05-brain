---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1046"
stix_relationship_id: "relationship--13d8aec7-3e49-41f8-b57c-475cdc0d9632"
---
# Relationship 8707: G0027 — uses → T1046

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) actors use the Hunter tool to conduct network service discovery for vulnerable systems.(Citation: Dell TG-3390)(Citation: Unit42 Emissary Panda May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13d8aec7-3e49-41f8-b57c-475cdc0d9632`.
