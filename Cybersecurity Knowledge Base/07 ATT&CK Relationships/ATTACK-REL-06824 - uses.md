---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "T1021.001"
stix_relationship_id: "relationship--81049d95-f06d-46ec-b2b9-29d8adf4127a"
---
# Relationship 6824: G1030 — uses → T1021.001

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) tunnels RDP traffic through deployed web shells to access victim environments via compromised accounts.(Citation: SentinelOne Agrius 2021) [Agrius](https://attack.mitre.org/groups/G1030) used the Plink tool to tunnel RDP connections for remote access and lateral movement in victim environments.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81049d95-f06d-46ec-b2b9-29d8adf4127a`.
