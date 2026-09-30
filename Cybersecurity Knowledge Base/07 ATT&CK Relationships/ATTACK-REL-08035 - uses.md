---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0604"
target_object: "T1572"
stix_relationship_id: "relationship--69a744c7-a971-4e21-b305-335801c539d1"
---
# Relationship 8035: S0604 — uses → T1572

**Source object:** [[01 ATT&CK/S0604 - Industroyer|S0604: Industroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Industroyer](https://attack.mitre.org/software/S0604) attempts to perform an HTTP CONNECT via an internal proxy to establish a tunnel.(Citation: Dragos Crashoverride 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69a744c7-a971-4e21-b305-335801c539d1`.
