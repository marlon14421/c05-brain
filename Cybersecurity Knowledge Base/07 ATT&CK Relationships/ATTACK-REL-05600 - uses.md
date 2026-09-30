---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1584.002"
stix_relationship_id: "relationship--4dfb2beb-4473-446e-beee-42729d8f87da"
---
# Relationship 5600: G1041 — uses → T1584.002

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.002 - DNS Server|T1584.002: DNS Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) modified Name Server (NS) items to refer to [Sea Turtle](https://attack.mitre.org/groups/G1041)-controlled DNS servers to provide responses for all DNS lookups.(Citation: Talos Sea Turtle 2019)(Citation: Talos Sea Turtle 2019_2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4dfb2beb-4473-446e-beee-42729d8f87da`.
