---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1572"
stix_relationship_id: "relationship--48f74ebb-3a7e-4b65-8e87-04d3bfe02914"
---
# Relationship 5650: S0038 — uses → T1572

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1572 - Protocol Tunneling|T1572: Protocol Tunneling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Duqu](https://attack.mitre.org/software/S0038) uses a custom command and control protocol that communicates over commonly used ports, and is frequently encapsulated by application layer protocols.(Citation: Symantec W32.Duqu)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48f74ebb-3a7e-4b65-8e87-04d3bfe02914`.
