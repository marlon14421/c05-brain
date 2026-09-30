---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "T1078.002"
stix_relationship_id: "relationship--2bad61ee-c880-422a-a918-f017f970fd81"
---
# Relationship 7689: G1030 — uses → T1078.002

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) attempted to acquire valid credentials for victim environments through various means to enable follow-on lateral movement.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2bad61ee-c880-422a-a918-f017f970fd81`.
