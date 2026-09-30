---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0117"
target_object: "T1046"
stix_relationship_id: "relationship--a423dc5c-c506-4cc5-b65c-0c9269d18fb6"
---
# Relationship 8008: S0117 — uses → T1046

**Source object:** [[01 ATT&CK/S0117 - XTunnel|S0117: XTunnel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[XTunnel](https://attack.mitre.org/software/S0117) is capable of probing the network for open ports.(Citation: Invincea XTunnel)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a423dc5c-c506-4cc5-b65c-0c9269d18fb6`.
